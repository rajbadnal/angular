pipeline {
  agent {
    node {
      label 'build'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm start'
      }
    }

  }
  environment {
    build = 'pipeline'
  }
}