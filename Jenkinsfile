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
    stage('confirmation') {
      steps {
        input(message: 'Deploy to Prod ?', id: 'dec1', ok: 'yes', submitter: 'Yes, No', submitterParameter: 'rY, rY')
      }
    }
  }
}