pipeline {
  agent any
  stages {
    stage('Master') {
      parallel {
        stage('Master') {
          steps {
            echo 'hello'
          }
        }

        stage('Development') {
          steps {
            echo 'world'
          }
        }

      }
    }

  }
}