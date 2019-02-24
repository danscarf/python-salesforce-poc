node('docker') {
  stage "Run in container (e.g. the php-7)"
  docker.image('php:7').inside {
    // run your command
    sh "phpunit"
  }
}
