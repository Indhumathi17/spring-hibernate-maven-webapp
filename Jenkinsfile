node{
stage('SCM checkout')
{ 
git'https://github.com/Indhumathi17/spring-hibernate-maven-webapp'
}
stage('clean')
{
  def mvnHome = tool name: 'maven1', type: 'maven'
  sh " ${mvnHome}/bin/mvn clean "
}
}
