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
                sh 'docker build . -t trainwithshubham/node-todo-test:latest'
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
