def code

node('master') {

  stage('Load') {
    code = load 'test.groovy'
  }

  stage('Execute') {
    code.Example1()
  }
}

code.Example2()
