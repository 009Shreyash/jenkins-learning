pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/009Shreyash/jenkins-learning.git', branch: 'main', credentialsId: '009shreyash')
      }
    }

    stage('Test') {
      steps {
        echo 'tested'
      }
    }

    stage('deploy') {
      steps {
        sleep 10
      }
    }

  }
}