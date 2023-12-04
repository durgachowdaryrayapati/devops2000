pipeline {
  agent any
  stages {
    stage('dev') {
      parallel {
        stage('dev') {
          steps {
            echo 'development stage'
          }
        }

        stage('test') {
          steps {
            echo 'test stage'
          }
        }

        stage('plugin') {
          steps {
            echo 'plugin'
          }
        }

      }
    }

    stage('QA') {
      steps {
        echo 'quality '
      }
    }

    stage('UPA') {
      steps {
        echo 'upa'
      }
    }

    stage('operate') {
      steps {
        echo 'operate'
      }
    }

  }
}