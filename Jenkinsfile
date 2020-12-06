pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        sh 'echo \'Starting build stage\''
      }
    }

    stage('Test') {
      steps {
        sh 'echo \'Starting test stage\''
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo \'Starting deploy stage\''
      }
    }

  }
}