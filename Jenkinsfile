pipeline {
  agent {
    node {
      label 'built-in'
    }

  }
  stages {
    stage('Build') {
      steps {
        withMaven(maven: 'M3') {
          sh 'mvn clean install'
        }

      }
    }

  }
}