node{
  stage('SCM Checkout'){
  git'https://github.com/Indhumathi17/spring-hibernate-maven-webapp'
  }
  //get maven home path
  stage('clear'){
  //def mvn_Home = tool name: 'Maven', type: 'Maven'
sh "${mvn_Home}/bin/mvn clean"

}
}
