pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'new jon', propagate: true, quietPeriod: 5, wait: true)
        archiveArtifacts 'a'
        pwd()
      }
    }
  }
}