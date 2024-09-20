pipeline {
    agent any
    stages {
        stage('Verify node version') {
            steps {
                sh 'node --version'
            }
        }
        stage('Verify npm version') {
            steps {
                sh 'npm --version'
            }
        }
        stage('Install Packages') {
            steps {
                sh 'npm i'
            }
        }
        stage('Build') {
            steps {
                sh 'npm run build'
            }
        }
        stage('Complete') {
            steps {
                sh 'echo Completed'
            }
        }
    }
}