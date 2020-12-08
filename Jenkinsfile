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
        input(message: 'Deploy to Stage', ok: 'Yes, let\'s do it!')
      }
    }

  }
  tools {
    maven 'Apache Maven 3.6.3'
    jdk 'jdk8'
  }
}