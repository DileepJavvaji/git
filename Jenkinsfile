pipeline {
  agent {
    docker {
      image 'maven:3.3-jdk-8 '
    }

  }
  stages {
    stage('Build') {
      agent {
        docker {
          image 'maven:3.3-jdk-8'
          args '-u-0:0'
        }

      }
      steps {
        echo 'Hello H r u from my first Jenkins build'
      }
    }
  }
}