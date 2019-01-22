pipeline {
  agent {
    docker {
      image 'jenkinsci/blueocean'
    }

  }
  stages {
    stage('print to console') {
      steps {
        echo 'hello, world'
      }
    }
  }
  environment {
    admin = 'admin'
  }
}