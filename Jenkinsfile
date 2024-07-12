pipeline {
    agent any

    stages {
        stage('Code') {
            steps {
                echo 'Pulling code from GitHub'
            }
        }
        stage('Build and Test') {
            steps {
                echo 'Building and testing the code'
            }
        }
        stage('Push') {
            steps {
                echo 'Pushing image to Docker Hub'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to Kubernetes'
            }
        }
    }
}
