pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        junit(testResults: 'reports/**/*.xml', allowEmptyResults: true, healthScaleFactor: 1, keepLongStdio: true)
      }
    }
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