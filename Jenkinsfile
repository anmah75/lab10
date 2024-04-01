pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/NaseemKhan005/react-bank-app'
            }
        }
        stage('Dependency Installation') {
            steps {
                sh 'npm install'  // Example command for installing dependencies
            }
        }
        // Define more stages for build, test, and deploy
    }
}

