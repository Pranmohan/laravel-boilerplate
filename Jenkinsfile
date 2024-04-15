pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Commands to build your project
                sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                // Commands to run tests
                sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                // Commands to deploy your project
                sh 'mvn deploy'
            }
        }
    }
}
