node{
  stage{ 'SCM checkout' }{
    git 'https://github.com/ddomnicraj/maven1.git'
  }
  stage{ 'compile the source codes' }{
    def defaultmaven = tool name: 'defaultmaven', type: 'maven'
    sh "${defaultmaven}/bin/mvn package"
  }  
}
