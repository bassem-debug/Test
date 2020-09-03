pipeline {
    agent { docker {
         image 'python' 
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
