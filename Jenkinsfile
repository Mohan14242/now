pipeline {
    agent any

    stages {
        stage('Parallel Build and Test') {
            parallel {
                // Build stage
                stage('Build') {
                    steps {
                        echo "Building the application..."
                        // Add your build commands here
                    }
                }
                
                // Test stage
                stage('Test') {
                    steps {
                        echo "Running tests..."
                        // Add your test commands here
                    }
                }
            }
        }
        
        stage('Deploy') {
            steps {
                echo "Deploying the application..."
                // Add your deployment commands here
            }
        }
    }
}
