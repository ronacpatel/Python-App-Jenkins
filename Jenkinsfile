pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'ls -al'
        sh 'python3 --version'
      }
    }
    
    stage('hello') {
      steps {
        sh 'python hello.py'
      }
    }
  }
}
