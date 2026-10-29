pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Getting source code from GitHub'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building  project'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing  project'
            }
        }
    }
}
