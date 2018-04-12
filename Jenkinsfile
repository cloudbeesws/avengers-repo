library 'SharedLibs'
pipeline {
  agent {
    docker {
      image 'maven:alpin'
    }
    
  }
  stages {
    stage('Stage-1') {
      steps {
        sh 'mvn -v'
      }
    }
    stage('Shared Lib') {
         steps {
             helloWorld("Jenkins")
         }
    }
  }
}
