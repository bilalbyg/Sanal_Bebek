pipeline {
  agent any
  stages {
    stage('Clean') {
      steps {
        sh 'mvn -DskipTests clean'
      }
    }

    stage('Compile') {
      steps {
        sh 'mvn -DskipTests compile'
      }
    }

  }
}