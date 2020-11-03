node{
  stage('SCM Checkout'){
   git 'https://github.com/nitinjmv/jenkins-jdk8/'
  }
  stage('Compile-Package'){
  sh 'mvn clean package'
  }

}
