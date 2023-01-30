pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        cat london.txt
      }
    }
    stage('Test') {
      steps {
        echo 'testing'
        cat sample
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
