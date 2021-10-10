pipeline {
  agent any
  stages {
    stage('Build1') {
      parallel {
        stage('Build1') {
          steps {
            sh 'echo 1'
          }
        }

        stage('') {
          steps {
            sh 'echo 3'
          }
        }

      }
    }

    stage('') {
      steps {
        sh 'echo 2'
      }
    }

  }
}