pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python --version'
      }
    }
     stage('Test Bat') {
           steps { 
                        bat 'C:\\Jenkins\\mytest.bat'
                        //bat 'start cmd.exe /c C:\\Jenkins\\mytest.bat'
                        //call C:\\Jenkins\\mytest.bat
        }
       }
    stage('hello') {
      steps {
        bat 'python hello.py'
      }
    }
  }
}
