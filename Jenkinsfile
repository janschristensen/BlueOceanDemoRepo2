pipeline {
  agent {
    docker {
      image 'docker.bintray.io/jfrog/artifactory-oss:latest'
      args '-d -p 8081:8081 docker.bintray.io/jfrog/artifactory-oss:latest'
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