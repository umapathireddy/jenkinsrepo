pipeline {
  agent any
  stages {
    stage('maven') {
      steps {
        sh '''pipeline {
    agent any

    stages {
        stage(\'Build\') {
            steps {
                echo \'Building..\'
            }
        }
        stage(\'Test\') {
            steps {
                echo \'Testing..\'
            }
        }
        stage(\'Deploy\') {
            steps {
                echo \'Deploying....\'
            }
        }
    }
}'''
        }
      }
<<<<<<< HEAD
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
=======
    }
  }
}
>>>>>>> parent of 8088941... adsfh
