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
    stage('error') {
      steps {
        writeFile(file: 'test', text: 'test')
      }
    }
    stage('gghh') {
      steps {
        echo 'trtttttttttttttttttttt'
      }
    }
  }
}