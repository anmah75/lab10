pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/ZoyaSumbul/Jenkins.git'
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

