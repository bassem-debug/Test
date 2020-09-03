pipeline {
    agent { docker {
      FROM image 'python:latest'    
            }
          }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
