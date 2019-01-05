pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        sh '''cd /home/ahoydeploy/deploy_area/gifter
gulp build:js'''
      }
    }
    stage(' End') {
      steps {
        pwd()
      }
    }
  }
}