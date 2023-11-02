pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building the project"'
                // Add actual build steps here
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests"'
                // Add test steps here
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying the application"'
                // Add deployment steps here
            }
        }
    }
}
