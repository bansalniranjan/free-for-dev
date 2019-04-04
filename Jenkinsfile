pipeline {
  agent any
  stages {
    stage('git checout') {
      parallel {
        stage('git checout') {
          steps {
            sh 'git info'
          }
        }
        stage('git failure') {
          steps {
            echo 'fail'
          }
        }
      }
    }
  }
}