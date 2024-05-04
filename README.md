pipeline {
    agent any
    stages {
        stage('Checkout 1') {
            steps {
                echo 'Latest code changes are committed.'
            }
        }
        stage('Checkout 2') {
            steps {
                echo 'Latest code changes are committed.'
            }
        }
        stage('Checkout 3') {
            steps {
                echo 'Latest code changes are committed.'
            }
        }
        stage('Build') {
            steps {
                echo 'Build successful! Please check the build logs.'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing completed! Please check the logs.'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployment completed! Please check the logs.'
            }
        }
    }
}
