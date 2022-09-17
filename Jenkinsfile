pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'ruby --version:latest'
      }
    }
    stage('hello') {
      steps {
        sh 'ruby test.rb'
      }
    }
  }
}
