pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''mvn compile
mvn clean install'''
      }
    }
  }
}