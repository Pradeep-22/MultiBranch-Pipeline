pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the project in test branch...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests in test branch...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application from test branch...'
            }
        }
    }
}
