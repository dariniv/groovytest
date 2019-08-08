def code

node('master') {

  stage('Load') {
    code = load 'test.groovy'
  }

  stage('Execute') {
    code.example1()
  }
}

code.example2()
