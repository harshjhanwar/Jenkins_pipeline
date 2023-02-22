pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'This is build step.'
      }
    }

    stage('Test') {
      steps {
        echo 'This is test step.'
        echo 'This is another message in test.'
      }
    }

    stage('Deploy') {
      steps {
        echo 'This is deploy stage.'
      }
    }

  }
}