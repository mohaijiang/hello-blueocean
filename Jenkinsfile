pipeline {
  agent any
  stages {
    stage('build') {
      agent {
        docker {
          image 'maven:3-openjdk-11'
        }

      }
      steps {
        sh 'mvn clean package'
      }
    }

  }
}