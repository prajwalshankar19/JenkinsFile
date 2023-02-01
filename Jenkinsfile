pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        powershell 'python Program.py'
      }
    }

    stage('Docker') {
      steps {
        powershell 'docker --version'
      }
    }

  }
}