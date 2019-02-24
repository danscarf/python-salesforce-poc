pipeline {
  agent {
    docker {
      image 'php:7'
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
        echo 'Starting the build...'
      }
    }
  }
  environment {
    node = 'docker'
  }
}