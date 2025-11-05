pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                checkout scm
                echo "Files checked out successfully"
            }
        }
        
        stage('Build') {
            steps {
                sh 'echo "Building project"'
                // Add your actual build commands here
            }
        }
    }
}
