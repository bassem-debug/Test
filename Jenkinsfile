pipeline {
    agent { docker { image 'python:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                print("bassem")
                sh 'chmod 777 script.py'
                sh '/var/lib/jenkins/workspace/pipe/script.py'

            }
        }
    }
}
