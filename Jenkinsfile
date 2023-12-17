pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               bat 'cd C:\Users\nishi\Desktop\git-sbdl\SBDL-Spark-Bulk-Data-Load'
            }
        }
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

