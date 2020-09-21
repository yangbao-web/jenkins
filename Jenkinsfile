Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh 'npm --version'
            }
        }
        stage('build') {
            steps {
                sh 'npm run build'
            }
        }
    }
}