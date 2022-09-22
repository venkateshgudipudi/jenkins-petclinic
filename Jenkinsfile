pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'pwd'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn clean'
            }
        }

        stage('New Stage') {
            steps {
                echo 'Testing..'
            }
	}
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
