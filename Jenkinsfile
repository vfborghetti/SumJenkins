pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        bat 'echo \'Starting build stage\''
        bat 'apt install cmake -y'
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