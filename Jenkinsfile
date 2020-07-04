pipeline {
  agent any


  stages {
    stage('gradwel Build') {
      steps {
              sh './gradlew'
      }
    }
    stage('gradwel Test') {
      steps {
        sh './gradlew test'
      }

    }
  }
}
