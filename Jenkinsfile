node{
  environment {
    PATH = "C:\Program Files\apache-maven-3.6.3\bin:$PATH"
  }
  stage('SCM Checkout'){
  git'https://github.com/Indhumathi17/spring-hibernate-maven-webapp'
  }
  //get maven home path
  stage('clear'){
  //def mvn_Home = tool name: 'Maven', type: 'maven'
//sh "${mvn_Home}/bin/mvn clean"
    bat 'mvn clean'

}
}
