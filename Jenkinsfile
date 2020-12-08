pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'good'
        echo 'food'
      }
    }

    stage('WHAT  to approve') {
      steps {
        input 'taper le code'
      }
    }

  }
  tools {
    maven 'Apache Maven 3.6.3'
    jdk 'jdk8'
  }
}