pipeline {
  agent any
  stages {
    stage('Exemple') {
      parallel {
        stage('Exemple') {
          steps {
            sleep(time: 3, unit: 'MINUTES')
          }
        }

        stage('Autres') {
          steps {
            sleep 3
            sleep(time: 2, unit: 'MINUTES')
          }
        }

      }
    }

  }
}