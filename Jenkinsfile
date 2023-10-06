pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'dir'
        bat 'cd C:\WINDOWS\SYSTEM32'
        bat 'python --version'
      }
    }
    stage('hello') {
      steps {
        bat 'python hello.py'
      }
    }
  }
}
