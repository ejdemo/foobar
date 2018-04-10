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
    stage('Stage2') {
      steps {
        input(message: 'Is it me you\'re looking for?', id: '42', ok: 'Y', submitter: 'foo', submitterParameter: 'foobar')
      }
    }
  }
}