pipeline {
  agent any
  stages {
    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            sh 'echo "test11111"'
          }
        }
        stage('test2') {
          steps {
            sh 'echo "test22222"'
          }
        }
      }
    }
    stage('test3') {
      steps {
        sh 'echo "test33333"'
      }
    }
  }
}
