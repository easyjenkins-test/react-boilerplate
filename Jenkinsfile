pipeline {
  agent any
  stages {
    stage('prebuild') {
      steps {
        echo 'helloworld'
      }
    }
    stage('') {
      steps {
        sh 'npm install && npm run setup'
      }
    }
  }
}