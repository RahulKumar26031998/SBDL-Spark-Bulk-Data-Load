pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               sh 'pipenv --python C:\Python sync'
            }
        }
        stage('Test') {
            steps {
               sh 'pipenv run pytest'
            }
        }
      }
   }

