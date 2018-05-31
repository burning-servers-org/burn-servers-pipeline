pipeline {
  agent any
  stages {
    stage('burning-servers') {
      steps {
        echo 'Servers are burning'
        sh '''pipeline {
   agent any
   stages {
      stage(\'Say Hello\') {
         steps {
            echo \'Hello World!\'   
            sh \'java -version\'
         }
      }
   }
}'''
        }
      }
    }
  }