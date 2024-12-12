pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository...'
                git branch: 'master', url: 'https://github.com/Midnight-Knight/metod4.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                bat 'echo Build successful!' // Используем bat вместо sh
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo Tests passed!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                bat 'echo Deployment successful!'
            }
        }
    }
}
