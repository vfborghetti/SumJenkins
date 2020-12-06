pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        bat 'echo \'Starting build stage\''
        bat 'install make'
      }
    }

    stage('Test') {
      steps {
        bat 'echo \'Starting test stage\''
      }
    }

    stage('Deploy') {
      steps {
        bat 'echo \'Starting deploy stage\''
      }
    }

  }
}