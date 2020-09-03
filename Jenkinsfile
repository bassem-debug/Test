pipeline {
    agent { docker {
         image 'python:3.5.1' 
         args '-v C:/Program Files (x86)/Jenkins/jobs/MyfirstPipeline/workspace/'
   
            }
          }
    stages {
        stage('build') {
            steps {
                bat 'python --version'
            }
        }
    }
}
