pipeline {
  agent any
  stages {
    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            sh 'echo "test1"'
          }
        }
        stage('test2') {
          steps {
            sh 'test2'
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