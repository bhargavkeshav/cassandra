pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          agent any
          environment {
            TEST = 'test'
          }
          steps {
            echo 'hello'
            sleep 10
            sh 'echo $TEST'
          }
        }

        stage('test1') {
          steps {
            sleep 9
          }
        }

      }
    }

    stage('testw4') {
      steps {
        sleep 88
      }
    }

    stage('Test') {
      steps {
        sleep 12
        archiveArtifacts '*'
      }
    }

  }
}