pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        echo 'Hello Blue Ocean'
      }
    }
    stage('build') {
      parallel {
        stage('build') {
          agent any
          steps {
            bat 'ping localhost'
          }
        }
        stage('Module1') {
          steps {
            bat 'ping localhost'
          }
        }
        stage('Module2') {
          steps {
            bat 'ping localhost'
          }
        }
      }
    }
    stage('deploy_Dev') {
      steps {
        bat 'ping localhost'
      }
    }
    stage('deploy_UAT') {
      steps {
        bat 'ping localhost'
      }
    }
    stage('deploy_PROD') {
      steps {
        bat 'ping localhost'
      }
    }
  }
}