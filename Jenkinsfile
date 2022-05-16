pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build Step'
                sleep 3
            }
        }
        stage('Test') {
            steps {
                echo 'Test step'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Step'
                sleep 3
            }
        }
        stage('Docker') {
            steps {
                echo 'Image step'
            }
        }
    }
}
