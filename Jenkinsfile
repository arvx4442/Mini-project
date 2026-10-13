
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'GitHub repository connected!'
            }
        }

        stage('Check Java') {
            steps {
                bat 'java -version'
                bat 'javac -version'
            }
        }
    }
}
