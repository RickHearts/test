pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            timestamps()
          }
        }

        stage('') {
          steps {
            echo 'Olá'
          }
        }

      }
    }

    stage('End') {
      steps {
        timestamps()
      }
    }

  }
}