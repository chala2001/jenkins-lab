pipeline {
    agent any
    stages {
        stage('Checkout info') {
            steps {
                sh 'ls -la'
                sh 'git log --oneline -3'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building commit ${GIT_COMMIT}"'
            }
        }
    }
}