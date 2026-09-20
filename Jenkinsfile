pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'GitHub code downloaded successfully'
                sh 'ls -la'
            }
        }
    }
}
