pipeline {
  agent any
  stages {
    stage('SonarQube analysis'){
      steps{
        withSonarQubeEnv(installationName: 'Sonarqube2', credentialsId: 'Sonarqube2') {
          sh "${tool("sonar_scanner")}/bin/sonar-scanner"
        }
      }
    }
    }
    }
