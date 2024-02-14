pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'echo Integrating Jenkins Pipeline with Github Webhook using Jenkinsfile'

            }
        }

        stage('test') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself-2'
                sh 'whoami'
                sh 'pwd'
                sh 'ls'
            }
        }
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself-3'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }

    }
}