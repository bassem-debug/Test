pipeline {
    agent { docker {
      FROM image 'python:latest' 
         args '-v /c:/program files (x86)/jenkins/jobs/myfirstpipeline/workspace/:/c:/program files (x86)/jenkins/jobs/myfirstpipeline/workspace/'
   
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
