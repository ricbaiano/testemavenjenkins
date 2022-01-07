pipeline{
  agent any
  
  stages {
  stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'null', jdk: '8', maven: 'Maven_Local', mavenSettingsConfig: 'null') {
        sh 'mvn clean install'
        }
      }
    }

  }
}
