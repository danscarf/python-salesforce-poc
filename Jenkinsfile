pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('Docker Info') {
      agent {
        node {
          label 'docker'
        }

      }
      steps {
        sh 'docker ps -a'
      }
    }
  }
}