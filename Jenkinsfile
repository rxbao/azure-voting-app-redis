@Library('github.com/devbyaccident/demo-shared-pipeline') _

pipeline {
  agent any
  stages {
    stage('Call Library Function with an arguement') {
      steps {
        script {
          helloArgs('Jenkins!')
        }
      }
    }
    stage('Call Additional Library Functions') {
      steps {
        script {
          helloArgs.goodbyeWorld('Jenkins!')
        }
      }
    }
  }
}