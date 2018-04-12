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
  }
}