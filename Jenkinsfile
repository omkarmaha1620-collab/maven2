pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo Building Maven Project'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Running Tests'
            }
        }

        stage('Package') {
            steps {
                sh 'echo Packaging Application'
            }
        }
    }
}
