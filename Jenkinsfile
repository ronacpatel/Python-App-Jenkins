pipeline {
  agent any

    stage("deploy") {
      steps {

        echo "Calling multi line batch command"
        bat '''
        call "C:\\path\\to\\batFile.bat"
        set myVar=exampleVar
        echo > Sometimes you want to keep environment variables set by the .bat script
        echo > so multiline script works best in this case: %myVar%
        '''
        
        echo "Calling single line batch command"
        bat "C:\\path\\to\\batFile.bat"
      stage('hello') {
      steps {
        bat 'python hello.py'
        
      }
    }
  }
}
