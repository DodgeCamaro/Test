pipeline {
  agent none

  stages {
    stage('Test') {
        agent {
            ecs {
                inheritFrom 'ecs'
            }
        }
        steps {
            sh 'echo hello'
        }
    }
  }
}
