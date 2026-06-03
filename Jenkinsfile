pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Jenkins successfully pulled this code directly from GitHub!'
            }
        }
        stage('test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('deploy') {
            steps{
                echo 'Deploying application...'
            }
        }
    }
}
