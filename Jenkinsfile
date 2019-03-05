pipeline {
  agent any
  stages {
    stage('asd') {
      parallel {
        stage('asd') {
          steps {
            echo 'test'
          }
        }
        stage('as') {
          steps {
            echo 'ss'
          }
        }
      }
    }
    stage('asdas') {
      parallel {
        stage('asdas') {
          steps {
            echo 'asas'
          }
        }
        stage('as') {
          steps {
            echo 'asdas'
          }
        }
      }
    }
  }
}