pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        echo 'Inizio'
      }
    }
    stage('create_otb_automator') {
      steps {
        sh 'create_otb_automator.sh'
      }
    }
  }
}