node{
  stage('SCM Checkout'){
  git'https://github.com/Indhumathi17/spring-hibernate-maven-webapp'
  }
  //get maven home path
  stage('clear'){
  #def mvn_Home = tool name: 'maven-3', type: 'maven'
#bat"${mvn_Home}/bin/mvn package"
bat 'mvn clean'
}
}
