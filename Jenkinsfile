pipeline {
    agent any
    
    stages {
        stage('checkout') {
            steps {
                // Checkout the source code from the Git repository
                checkout scm
                
                // Install dependencies
                
            }
        }
        
        stage('Test') {
            steps {
                // Run tests
                sh 'npm install'
            }
        }
        
        stage('Deploy') {
            steps {
                
                sh 'npm install'
                
                sh 'npm start'
            }
        }
    }
}
