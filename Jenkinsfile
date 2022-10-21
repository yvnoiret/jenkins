pipeline {
  agent any
  stages {
    stage('Message') {
      steps {
        echo 'Début du pipeline'
      }
    }

    stage('Message de fin') {
      steps {
        echo 'Fin du pipeline'
      }
    }

    stage('Step 1') {
      steps {
        sh 'ls -l'
      }
    }

  }
}