pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        bat 'echo \'Starting build stage\''
        bat 'install cmake'
      }
    }

    stage('Test') {
      steps {
        bat 'echo \'Starting test stage\''
        bat '"\\"C:\\Windows\\System32\\config\\systemprofile\\AppData\\Local\\Jenkins\\.jenkins\\workspace\\SumJenkins_main\\Debug\\main.cpp\\""'
      }
    }

    stage('Deploy') {
      steps {
        bat 'echo \'Starting deploy stage\''
      }
    }

  }
}