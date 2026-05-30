pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello from Jenkins!'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
        
        stage('Cleanup') {
            steps {
                echo 'Cleaning up...'
            }
        }

        stage('Notify') {
            steps {
                echo 'Sending notifications...'
            }
        }

    }
}