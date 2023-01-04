pipeline {
  agent { label 'npm' }

  stages {
    
    stage('Install') {
      steps {
          sh 'npm install'
      }
    }

    stage('Check') {
      steps {
          sh 'npm run check'
      }
    }

    stage('Test') {
      steps {
          sh 'npm run test'
          sh 'npm run verify'
      }
    }

    stage('Build') {
      steps {
          sh 'npm run build'
      }
    }

  }
}