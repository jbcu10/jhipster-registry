pipeline {
  agent any
  stages {
    stage('Preparation') {
      steps {
        sh 'java -version'
      }
    }
    stage('Build') {
      steps {
        sh './mvnw -Pprod package'
      }
    }
  }
}