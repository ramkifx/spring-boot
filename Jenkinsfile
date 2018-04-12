pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('shell script') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}