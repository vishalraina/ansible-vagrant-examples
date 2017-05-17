pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo starting build'
      }
    }
    stage('test') {
      steps {
        echo 'hello'
      }
    }
    stage('deploy') {
      steps {
        echo 'hello'
      }
    }
    stage('Approvals') {
      steps {
        stash 'Vishal'
      }
    }
  }
}