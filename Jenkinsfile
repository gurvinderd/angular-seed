pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'djangodocker', propagate: true)
        archiveArtifacts 'a'
        pwd()
      }
    }
  }
}