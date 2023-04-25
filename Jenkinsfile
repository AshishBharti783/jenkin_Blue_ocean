pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "hi jenkin"'
      }
    }

    stage('test') {
      steps {
        echo 'echo is working :)'
      }
    }

    stage('testing') {
      steps {
        echo 'working'
        sleep 10
      }
    }

    stage('deploy') {
      steps {
        echo 'deploying you echo work'
        sh 'ls'
      }
    }

    stage('done') {
      steps {
        echo 'Successfully Done....'
      }
    }

  }
}