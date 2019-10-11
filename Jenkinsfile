node{
  stage{ 'SCM checkout' }{
    git ''
  }
  stage{ 'compile the source codes' }{
    def defaultmaven = tool name: 'defaultmaven', type: 'maven'
    sh 'mvn package'
  }  
}
