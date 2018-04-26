pipeline {
  agent any
  stages {
    stage('clone repository') {
      steps {
        echo 'Starting the pipeline'
        build(job: 'job1', propagate: true, wait: true)
      }
    }
  }
}