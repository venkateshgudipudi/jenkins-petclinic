pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'pwd'
            }
        }
        stage('Test') {
            steps {
                bat 'mvn clean'
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
