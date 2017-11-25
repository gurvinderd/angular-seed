pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'djangodocker', propagate: true, quietPeriod: 5, wait: true)
        archiveArtifacts 'a'
        pwd()
      }
    }
  }
}