pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'capstone_pipeline'
        sh './mvnw clean compile'
      }
    }

    stage('Unit Test') {
      steps {
        sh './mvnw capstone'
      }
    }

  }
}