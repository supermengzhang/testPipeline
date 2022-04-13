pipeline {
  agent {
    docker {
      image 'test'
      args 'aa'
    }

  }
  stages {
    stage('testaa') {
      steps {
        sh 'echo "test"'
      }
    }

  }
}