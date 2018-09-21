pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'ADD docker/ECS build and push into ECR repo'
            }
            post {
		success{
			 docker ps
			}
		}
        }
        stage('Test') {
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
