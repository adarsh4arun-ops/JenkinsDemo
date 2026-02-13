pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'C:/Users/student/AppData/Local/Programs/Python/Python314 bin_search.py'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
