pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            bat 'echo hi'
          }
        }

        stage('test') {
          steps {
            sleep 30
          }
        }

      }
    }

  }
}