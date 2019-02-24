pipeline {
  agent {
    node {
      label 'build-docker'
    }

  }
  stages {
    stage('error') {
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