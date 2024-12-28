pipeline {
    agent any

    stages {
        stage('Starting') {
            steps {
                echo 'Starting....'
            }
        }
        stage('Sleep') {
            steps {
                sh "sleep 25"
            }
        }
        stage('Execute') {
            steps {
                echo 'Executed with thanks'
            }
        }
    }
}
