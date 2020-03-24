pipeline {
  agent any
  stages {
    stage('Build 1') {
      parallel {
        stage('Build 1') {
          steps {
            sh 'echo "This is my first Build"'
          }
        }

        stage('Build 2') {
          steps {
            sh 'echo "This is my second Build"'
          }
        }

      }
    }

    stage('Test') {
      steps {
        sh 'echo "This test is completely successful"'
      }
    }

  }
}