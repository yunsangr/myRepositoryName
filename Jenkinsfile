pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            args '-p 3000:3000'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm --version'
                sh 'ls -al'
                sh 'pwd'
            }
        }
        stage('Install') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo "Let's implement test stage soon..."
            }
        }
        stage('Run Server') {
            steps {
                echo "Running Server..."
                sh "nohup npm run serve &"
            }
        }
    }
}