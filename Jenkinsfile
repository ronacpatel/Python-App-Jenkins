pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'ls -al'
        sh 'python --version'
      }
    }
    
    stage('hello') {
      steps {
        sh 'python hello.py'
      }
    }
  }
}
