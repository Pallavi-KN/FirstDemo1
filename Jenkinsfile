pipeline {
  agent {
    node {
      label 'mylocal'
    }

  }
  stages {
    stage('Init') {
      steps {
        echo 'Hello Blue Ocean'
      }
    }
    stage('build') {
      steps {
        sh '''cd C:\\Users\\External.Pallavi.Har\\GitRepo\\FirstDemoLocal\\FirstDemo
mvn clean install
'''
      }
    }
  }
}