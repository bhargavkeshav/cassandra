pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'hello'
            sleep 10
            sh 'echo "hello"'
          }
        }

        stage('test1') {
          steps {
            sleep 9
          }
        }

      }
    }

    stage('testw3') {
      steps {
        sleep 88
      }
    }

    stage('Test') {
      steps {
        sleep 12
      }
    }

  }
}