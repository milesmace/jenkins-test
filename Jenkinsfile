pipeline {
  agent {
    docker { image 'node:20-alpine' }
  }

  stages {
    stage('Get Version') {
      steps {
        sh 'node --version'
      }
    }

    stage('Get Version') {
      steps {
        sh 'node run.js'
      }
    }
  }
}
