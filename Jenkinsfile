pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python --version'
      }
    stage('build') {
      cmd_exec('echo "Buils starting..."')
      cmd_exec('echo "dir /a /b"')
}

def cmd_exec(command) {
    return bat(returnStdout: true, script: "${command}").trim()
}
    
    stage('hello') {
      steps {
        bat 'python hello.py'
      }
    }
  }
}
