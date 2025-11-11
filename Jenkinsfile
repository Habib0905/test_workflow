pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Pull your code from GitHub
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
            }
        }
    }

    post {
        always {
            echo "Pipeline finished — cleaning up workspace."
        }
    }
}
