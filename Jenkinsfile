pipeline {
  agent {
    docker { image 'node:18-alpine' }
  }
  stages {
    stage('Install') {
      steps {
        sh 'npm install'
      }
    }
    stage('Test') {
      steps {
        sh 'node --version'
        sh 'npm test'
      }
    }
  }
}