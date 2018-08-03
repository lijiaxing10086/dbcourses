pipeline {
  agent any
  stages {
    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            sh 'pwd'
          }
        }
        stage('test2') {
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