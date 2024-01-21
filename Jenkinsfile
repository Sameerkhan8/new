pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Hello World'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Hello World/......'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Hello World'
            }
        }
    }

    post {
        success {
            echo 'Hello World successfully built, tested, and deployed!'
        }
        failure {
            echo 'Hello World build, test, or deployment failed.'
        }
    }
}
