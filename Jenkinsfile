pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        parallel(
          "1": {
            echo 'hello'
            
          },
          "2": {
            echo 'hello2'
            
          }
        )
      }
    }
    stage('3') {
      steps {
        echo 'done'
      }
    }
  }
}