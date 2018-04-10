pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('Stage1') {
      steps {
        sh 'echo \'hello world\''
      }
    }
  }
}