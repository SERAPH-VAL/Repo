pipeline {
    agent any
    triggers {
        pollSCM('H/1 * * * *')
    }
    stages {
        stage('Build') {
            steps {
                script {
                    echo 'Building from test branch'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    echo 'Testing from test branch'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    echo 'Deploying from test branch'
                }
            }
        }
    }
}
