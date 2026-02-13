pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'C:/Users/student/AppData/Roaming/Python/Python313/python bin_search.py'
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
