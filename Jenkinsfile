pipeline {
  agent any
  stages {
    stage('node') {
      steps {
        sleep 2
      }
    }
    stage('start') {
      steps {
        echo 'starting...........'
      }
    }
    stage('') {
      steps {
        writeFile(file: 'test', text: 'test')
      }
    }
  }
}