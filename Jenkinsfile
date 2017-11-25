pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'djangodocker', propagate: true, wait: true)
        archiveArtifacts 'a'
        pwd()
      }
    }
  }
}