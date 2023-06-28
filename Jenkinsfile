pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'pwd'
          }
        }

        stage('test') {
          steps {
            echo 'hi there'
          }
        }

        stage('secondtest') {
          steps {
            echo 'secondtest'
          }
        }

      }
    }

  }
}