pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('Docker Info') {
      agent {
        docker {
          image 'python:latest'
        }

      }
      steps {
        sh 'python -v'
      }
    }
  }
}