pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        bat 'echo This is $BUILD_NUMBER from $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}