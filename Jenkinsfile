pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out pipeline'
            }
        }

        stage('Build') {
            steps {
                echo 'Building pipeline'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing pipeline'
            }
        }

        stage('Package') {
            steps {
                echo 'Packaging pipeline'
            }
        }
    }

    post {
        success {
            echo 'Successfully built'
        }

        failure {
            echo 'Build failed'
        }
    }
}
