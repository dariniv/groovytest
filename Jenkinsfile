def code

node('java-agent') {

  stage('Load') {
    code = load 'example.groovy'
  }

  stage('Execute') {
    code.example1()
  }
}

code.example2()
