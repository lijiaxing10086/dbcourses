pipeline {
  agent any
  stages {
    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            sh 'pwd'
            sh 'ls -l'
          }
        }
        stage('test3') {
          steps {
            sh 'echo "test2"'
          }
        }
      }
    }
    stage('test3') {
      steps {
        sh 'echo "test3"'
      }
    }
  }
}