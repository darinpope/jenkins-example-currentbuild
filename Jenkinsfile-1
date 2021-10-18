pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh 'echo Hello World'
        echo "Build number is ${currentBuild.number}"
      }
    }
  }
}