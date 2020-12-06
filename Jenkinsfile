pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        bat 'echo \'Starting build stage\''
        bat '"\\"C:\\\\Program Files (x86)\\\\Microsoft Visual Studio\\\\2019\\\\Community\\\\MSBuild\\\\Current\\\\bin\\\\MSBuild.exe\\""'
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