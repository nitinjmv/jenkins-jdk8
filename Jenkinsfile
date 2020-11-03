node{
  stage('SCM Checkout'){   
   git 'https://github.com/nitinjmv/jenkins-jdk8/'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: 'maven', type: 'maven'
    sh "${mvnHome}"/bin/mvn clean package"
  }

}
