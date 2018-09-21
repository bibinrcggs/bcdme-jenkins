pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                docker ps
                echo 'build'
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
