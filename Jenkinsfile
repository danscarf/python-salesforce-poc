pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('Run in container (e.g. the php-7)') {
      agent {
        docker {
          image 'php:7'
        }

      }
      steps {
        sh '''env
docker'''
        echo 'this is a message'
      }
    }
    stage('with docker') {
      agent {
        docker {
          image 'php:7'
        }

      }
      steps {
        sh 'phpunit'
      }
    }
  }
}