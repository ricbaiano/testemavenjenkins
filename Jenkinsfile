pipeline{
  agent any
  
  stages {
  stage('maven install') {
    steps {
      withMaven(maven: 'Maven_Local') {
        sh 'mvn clean install'
        }
      }
    }
  }
  
}
