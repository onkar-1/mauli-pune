pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pwd
ls
'''
      }
    }

    stage('test') {
      steps {
        echo 'radhe radhe'
      }
    }

    stage('deploy on test') {
      steps {
        sleep 10
      }
    }

    stage('prod') {
      steps {
        echo 'om'
      }
    }

    stage('end') {
      steps {
        sleep 2
      }
    }

  }
}