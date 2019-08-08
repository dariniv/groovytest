def code

node('master') {

  stage('Load') {
    code = load 'test.groovy'
  }

  stage('Execute') {
    code.test1()
  }
}

code.test2()
