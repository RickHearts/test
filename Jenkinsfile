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
            echo 'Ol�'
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