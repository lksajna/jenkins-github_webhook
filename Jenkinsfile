pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'This is stage checkout'
            }
        }
        stage('Build Backend') {
            steps {
                echo 'This satge will build the backend code.'
            }
        }
        stage('Build Frontend') {
            steps {
                sh 'javac Hello.java'
                sh 'java Hello'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Will Deploy the code.'
            }
        }
        stage('Test') {
            steps {
                echo 'Tests will be executed in this stage'
            }
        }
        stage('Release') {
            steps {
                echo 'Release is done successfully'
            }
        }
    }
}
