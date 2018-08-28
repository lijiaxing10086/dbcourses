pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        echo '${WORKSPACE}'
        sh 'echo ${WORKSPACE}'
      }
    }
  }
  environment {
    test = '123'
  }
}