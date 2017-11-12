pipeline {
  agent {
    docker {
      image 'docker.bintray.io/jfrog/artifactory-oss'
      args 'latest'
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