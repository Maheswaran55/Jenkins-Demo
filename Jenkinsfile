pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Getting Source Code'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building GitHub Project'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Testing GitHub Project'
            }
        }

        stage('Complete') {
            steps {
                echo 'GitHub Integration Successful'
            }
        }
    }
}
