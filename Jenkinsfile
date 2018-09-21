pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'apt install docker'
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
