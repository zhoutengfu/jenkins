pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'hello word'
          }
        }

        stage('ccc') {
          steps {
            sh 'git --version'
          }
        }

      }
    }

  }
}