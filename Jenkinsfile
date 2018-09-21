pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh "docker ps"
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
