pipeline {
  agent {
    node {
      label '18'
    }
    
  }
  stages {
    stage('pg') {
      parallel {
        stage('b') {
          steps {
            echo 'kaishi'
            sh 'df -h'
            sh 'ansible -v'
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