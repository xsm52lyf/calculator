pipeline {
  agent {
    docker {
      image 'nodejs'
    }

  }
  stages {
    stage('Build stage') {
      steps {
        sh '''npm install 
npm run build'''
      }
    }

  }
}