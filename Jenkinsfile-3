@Library("shared-library") _
pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh 'echo Hello World'
        addSidebarLink(url:'https://www.cloudbees.com/', text:'CloudBees website', icon:'/userContent/cloudbees.png')
      }
    }
  }
}