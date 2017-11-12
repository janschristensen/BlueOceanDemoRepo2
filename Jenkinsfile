pipeline {
  agent {
    docker {
      image 'docker.bintray.io/jfrog/artifactory-oss:latest'
    }
    
  }
  stages {
    stage('Clone') {
      steps {
        echo 'Hello Clone'
      }
    }
  }
}