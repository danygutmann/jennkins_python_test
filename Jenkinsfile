pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python --version'
      }
    }
    stage('Script1') {
      steps {
        sh 'python hello01.py'
      }
    }
    stage('Script2') {
      steps {
        sh 'python hello02.py'
      }
    }
  }
}
