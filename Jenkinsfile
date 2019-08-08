  stage('Load') {
    code = load 'test.groovy'
  }

  stage('Execute') {
    code.test()
    }
  }

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
}
