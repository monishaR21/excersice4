pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'npm install' // Install dependencies
                sh 'npm run build' // Build LuciBot
            }
        }
        
        stage('Test') {
            steps {
                sh 'npm run test' // Run tests
            }
        }
    }
}
