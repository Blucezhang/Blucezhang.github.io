pipeline {
  agent any
  stages {
    stage('hi') {
      steps {
        echo 'hello word'
      }
    }
    stage('hello') {
      steps {
        echo 'new node'
      }
    }
    stage('node-3') {
      steps {
        echo 'message-2'
      }
    }
    stage('node-4') {
      steps {
        timestamps() {
          writeFile(encoding: 'utf-8', text: '1', file: '123.txt')
        }
        
      }
    }
  }
}