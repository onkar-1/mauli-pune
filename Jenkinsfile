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
        build(job: 'choice', propagate: true, quietPeriod: 2, waitForStart: true)
      }
    }

    stage('end') {
      steps {
        sleep 2
      }
    }

  }
}