node('master') 
{
  stage('ContinuousDownload') 
  {
    git 'https://github.com/keshavr21/maven_test.git'
  } 
  stage('ContinuousBuild') 
  {
    sh '/opt/maven/bin mvn package'
  } 
}
