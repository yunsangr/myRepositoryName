pipeline {
    agent { dockerfile true
    }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                echo 'hello jenkins!'
            }
        }
    }
}