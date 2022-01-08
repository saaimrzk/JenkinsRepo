pipeline {
    agent any

    stages {
        stage('Gather Facts') {
            steps {
                echo 'Gathering Facts required for the pipeline'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the deployment'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project'
            }
        }
        stage('Release') {
            steps {
                echo 'Releasing the project'
            }
        }
    }
}
