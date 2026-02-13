pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'python bin_search.py'
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
