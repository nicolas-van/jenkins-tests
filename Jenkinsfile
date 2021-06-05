pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                sh 'echo user: $USER'
                sh 'node --version'
                sh 'npm --version'
            }
        }
    }
}
