pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "hello"'
      }
    }

    stage('stage2') {
      steps {
        echo 'welcome'
      }
    }

    stage('stage3') {
      steps {
        sh 'touch file.txt'
      }
    }

  }
}