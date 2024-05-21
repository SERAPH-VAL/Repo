pipeline {
    agent any
    triggers {
        pollSCM('H/2 * * * *')
    }
    stages {
        stage('Build') {
            steps {
                script {
                    echo 'Building from prod branch'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    echo 'Testing from prod branch'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    echo 'Deploying from prod branch'
                }
            }
        }
    }
}
