pipeline {
  agent {
    node {
      label 'dev'
    }

  }
  stages {
    stage('build') {
      steps {
        sh '''mvn compile
mvn clean install'''
      }
    }
  }
}