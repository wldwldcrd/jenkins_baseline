pipeline {
    agent {
        docker { image 'python:3.10.1-alpine' }
    }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                echo 'Greetings traveler! I want to invite you to Russia'
            }
        }
    }
}

