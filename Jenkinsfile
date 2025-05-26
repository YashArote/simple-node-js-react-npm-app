pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/YashArote/simple-node-js-react-npm-app'
            }
        }
        stage('Install') {
            steps {
                // Install dependencies (for Node.js)
                bat 'npm install'
            }
        }
        stage('Test') {
            steps {
                // Run tests (for Node.js)
                bat 'npm test'
            }
        }
        stage('Build') {
            steps {
                // Build the project (for Node.js)
                bat 'npm run build'
            }
        }
    }
}
