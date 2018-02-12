pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build Start'
          }
        }
        stage('') {
          steps {
            echo 'gdg'
          }
        }
      }
    }
    stage('test') {
      steps {
        echo 'starttest'
      }
    }
    stage('deploy') {
      steps {
        echo 'disploy'
      }
    }
  }
}