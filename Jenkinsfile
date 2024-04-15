pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                // checkout code from git
                git 'https://github.com/Pranmohan/laravel-boilerplate.git'
            }
        }
        stage('Test') {
            steps {
                // Commands to run tests
                sh 'echo "test the code = working fine"'
            }
        }
        stage('check code') {
            steps {
                // Commands to run tests
                sh 'echo "test the code = working fine"'
            }
        }
        stage('Deploy') {
            steps {
                // Commands to deploy your project
                sh 'echo "deploy the code successfully second time"'
            }
        }
    }
}
