pipeline {
  agent {
    node {
      label 'node-20220120'
    }

  }
  stages {
    stage('start') {
      parallel {
        stage('start') {
          steps {
            sh '{}'
          }
        }

        stage('') {
          steps {
            git(url: 'http://test', branch: 'develop', credentialsId: 'qazwsx')
          }
        }

      }
    }

  }
  environment {
    JAVA_HOME = '/usr/toos/jdk1.8'
  }
}