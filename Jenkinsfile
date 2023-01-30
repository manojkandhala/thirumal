pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'cat london.txt'
      }
    }
    stage('Test') {
      steps {
        echo 'testing'
        sh 'cat sample'
      }
    }
    stage('Deploy') {
      steps {
        echo "`ls` \n these are the files"
        echo 'Deploying...'
      }
    }
  }
}
