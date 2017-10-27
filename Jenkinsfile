pipeline {
  agent any
  stages {
    stage('pg') {
      parallel {
        stage('b') {
          steps {
            echo 'kaishi'
          }
        }
        stage('t') {
          steps {
            echo 'fdffd'
          }
        }
      }
    }
    stage('') {
      steps {
        echo 'rrr'
      }
    }
  }
}