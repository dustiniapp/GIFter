pipeline {
  agent any
  stages {
    stage('Stage 1') {
      parallel {
        stage('Stage 1') {
          steps {
            echo 'Code has been pulled'
          }
        }
        stage('test a') {
          steps {
            echo 'test a'
          }
        }
      }
    }
    stage('stage 2') {
      parallel {
        stage('stage 2') {
          steps {
            echo 'test 2'
          }
        }
        stage('test b') {
          steps {
            echo 'test b'
          }
        }
      }
    }
  }
}