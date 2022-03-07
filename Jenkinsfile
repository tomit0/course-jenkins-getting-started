pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'echo "This is the $BUILD_NUMBER of the demo $DEMO"'
      }
    }

  }
  environment {
    demo = ''
  }
}