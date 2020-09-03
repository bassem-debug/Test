pipeline {
    agent { docker { image 'python:3.5.1','$HOME } }
    stages {
        stage('build') {
            steps {
                bat 'python --version'
            }
        }
    }
}
