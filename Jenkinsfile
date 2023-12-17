pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               bat 'pipenv --python Python3.7 sync'
            }
        }
        stage('Test') {
            steps {
               bat 'pipenv run pytest'
            }
        }
      }
   }

