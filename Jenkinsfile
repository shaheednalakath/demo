pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello from Jenkins!'
            }
        }
    }

    stages {
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
    stages {
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}