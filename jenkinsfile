pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                powershell 'Write-Output "Checking out"'
            }
        }

        stage('Build') {
            steps {
                powershell 'javac -version'
            }
        }

        stage('Deploy') {
            steps {
                powershell 'Write-Output "Deploying the application"'
            }
        }
    }
}
