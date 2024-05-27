pipeline {
  agent {
    label 'agent-01'
  }
  stages {
    stage('hello') {
      steps {
        echo "hello"
        sh 'echo \'Build Number: $BUILD_NUMBER\''
      }
    }

  }
}