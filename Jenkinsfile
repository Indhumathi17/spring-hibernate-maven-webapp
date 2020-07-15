node{
stage('SCM checkout')
{ 
git'https://github.com/Indhumathi/spring-hibernate-maven-webapp'
}
stage('clean')
{
  def mvnHome = tool name: 'maven1', type: 'maven'
  bat " ${mvnHome}/bin/mvn clean "
}
}
