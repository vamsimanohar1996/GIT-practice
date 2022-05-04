pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sleep 2
        echo 'building script'
        sh 'echo "you can run all other commands"'
      }
    }

  }
  environment {
    task = 'demo'
  }
}