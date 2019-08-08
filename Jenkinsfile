 
pipeline {
  agent any
  stages {
  stage('Stage 1') {
      steps {
        script {
          echo 'Stage 1'
        }
      }
    }
  stage('Stage 2') {
      steps {
        script {
          echo 'Stage 2'
        }
      }
    }
   

def code

node('java-agent') {
  stage('Checkout') {
    checkout scm
  }

  stage('Load') {
    code = load 'example.groovy'
  }

  stage('Execute') {
    code.example1()
  }
}

code.example2()
  }
}
