pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      parallel {
        stage('Checkout Code') {
          steps {
            git(url: 'https://github.com/alen-marutyan/test-jenkins', branch: 'dev', changelog: true)
          }
        }

        stage('Print Checkout log') {
          steps {
            echo 'I got checkout!'
          }
        }

      }
    }

  }
}