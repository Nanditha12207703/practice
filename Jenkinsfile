pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Build stage..."
            }
        }
        stage('Deploy') {
            when {
                branch 'master'
            }
            steps {
                echo "Deploying..."
            }
        }
    }
}
