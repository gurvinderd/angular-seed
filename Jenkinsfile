pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build 'djangodocker'
        archiveArtifacts 'a'
        pwd()
      }
    }
  }
}