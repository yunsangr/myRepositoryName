pipeline {
    agent any
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
                echo "Running Server... Not going to run actually..."
            }
        }
    }
}