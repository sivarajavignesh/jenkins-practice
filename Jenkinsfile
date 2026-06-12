pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                sh 'echo Code pulled from GitHub'
            }
        }
        stage('Build') {
            steps {
                sh 'echo Building the app...'
            }
        }
        stage('Test') {
            steps {
                sh 'echo Running tests...'
            }
        }
    }
}
