pipeline {
    agent { docker { image 'python:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                print("bassem")
                sh 'pipe/script.py'                
            }
        }
    }
}
