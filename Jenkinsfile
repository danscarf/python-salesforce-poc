pipeline {
  agent {
    node {
      label 'docker'
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
        sh 'hostname'
      }
    }
  }
}