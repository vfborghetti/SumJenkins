pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        bat 'echo \'Starting build stage\''
        bat '"\\"C:\\Program Files (x86)\\Microsoft Visual Studio\\2019\\Community\\MSBuild\\Current\\Bin\\MSBuild.exe\\""'
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