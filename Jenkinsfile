pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        cleanWs(cleanWhenAborted: true)
      }
    }
    stage('deploy') {
      steps {
        validateDeclarativePipeline 'C:\\Users\\Reddy\\Documents\\Bluetooth Folder\\thumbs'
      }
    }
  }
}