pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python --version'
      }
    }
    environment {

    PATH = "C:\\WINDOWS\\SYSTEM32"

}
    stage('hello') {
      steps {
        bat 'python hello.py'
      }
    }
  }
}
