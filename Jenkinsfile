pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                echo 'Checking out source code from GitHub'
                checkout scm
            }
        }

        stage('Build Backend Image') {
            steps {
                echo 'Simulating backend Docker image build'
                echo 'Backend image build successful'
            }
        }

        stage('Deploy Backend Containers') {
            steps {
                echo 'Simulating deployment of backend containers'
                echo 'backend1 started'
                echo 'backend2 started'
            }
        }

        stage('Deploy NGINX Load Balancer') {
            steps {
                echo 'Simulating NGINX load balancer deployment'
                echo 'NGINX load balancer running on port 80'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully'
        }
        failure {
            echo 'Pipeline failed. Check console logs for errors.'
        }
    }
}
