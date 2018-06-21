pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        echo 'Hello Blue Ocean'
      }
    }
    stage('build') {
      agent any
      steps {
        bat 'ping localhost'
      }
    }
  }
}