pipeline {
  agent any
  stages {
    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            sh 'echo "test11111"'
            input(message: 'input1', id: 'input1', ok: 'input1')
            echo 'aaa'
            input(message: 'input2', id: 'input2', ok: 'input2')
            echo 'bbb'
            echo 'ccc'
          }
        }
        stage('error') {
          steps {
            echo 'xxxx'
            sleep 60
          }
        }
      }
    }
    stage('test3') {
      steps {
        echo 'aaa'
      }
    }
  }
}