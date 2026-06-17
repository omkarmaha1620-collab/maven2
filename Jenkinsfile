pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/omkarmaha1620-collab/maven2.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn compile'
            }
        }

        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }

        stage('Package') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
