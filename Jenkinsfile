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
                bat 'py app.py'
            }
        }

        stage('Test') {
            steps {
                bat 'py test.py'
            }
        }

    }
}
