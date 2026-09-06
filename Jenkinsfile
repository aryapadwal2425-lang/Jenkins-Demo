pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/aryapadwal2425/Jenkins-Demo.git'
            }
        }

        stage('Build') {
            steps {
                bat 'python app.py'
            }
        }

        stage('Test') {
            steps {
                bat 'python test.py'
            }
        }

    }
}
