pipeline {
  agent any
  stages {
    stage('pg') {
      parallel {
        stage('b') {
          steps {
            echo 'kaishi'
            sh 'df -h'
          }
        }
        stage('t') {
          steps {
            echo 'fdffd'
          }
        }
      }
    }
    stage('error') {
      steps {
        echo 'rrr'
      }
    }
  }
}