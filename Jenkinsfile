pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build 'new jon'
        archiveArtifacts 'a'
        pwd()
      }
    }
  }
}