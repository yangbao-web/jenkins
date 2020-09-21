pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh 'npm --version'
            }
        }
        stage('install') {
            steps {
                sh 'npm install'
            }
        }
        stage('build') {
            steps {
                sh 'npm run build'
            }
        }
    }
}