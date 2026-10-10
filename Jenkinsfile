pipeline {
    agent none 
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out source code from repository...'
            }
        }
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
    post {
        success {
            echo 'Pipeline completed successfully!'
        }
    }
}
