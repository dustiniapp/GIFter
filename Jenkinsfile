pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        echo 'Code has been pulled'
      }
    }
    stage(' End') {
      steps {
        pwd()
        waitUntil() {
          echo 'ok'
        }

      }
    }
  }
}