pipeline {
  agent any
  tools {
      go 'go1.17'
  }
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
      }
    }

  }
}
