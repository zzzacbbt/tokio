pipeline {
  agent {
    docker {
      image 'python:3.7.2'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'pip install -U pytest'
      }
    }
  }
}