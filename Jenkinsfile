pipeline {
  agent {
    label 'agent-01'
  }
  stages {
    stage('hello') {
      steps {
        echo '"Hello, Build Number: $BUILD_NUMBER"'
        sh 'echo "Build Number: $BUILD_NUMBER"'
      }
    }

  }
}