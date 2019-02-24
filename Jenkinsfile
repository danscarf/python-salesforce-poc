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
          image 'php:7'
        }

      }
      steps {
        sh 'docker ps -a'
      }
    }
  }
}