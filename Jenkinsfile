pipeline {
    agent { docker {
         image 'python:3.5.1' 
         args '-v /c:/program files (x86)/jenkins/jobs/myfirstpipeline/workspace/'
   
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
