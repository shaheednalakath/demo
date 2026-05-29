pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building application...'
                // Add build commands here
            }
        }

        stage('Test') {
            steps {
                echo 'Running unit tests...'
                // Add test commands here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Starting deployment demo...'
                // Add deployment commands here

                echo 'Running post-deployment verification...'
                echo 'Sending deployment notification...'
            }
        }
    }
}