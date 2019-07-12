pipeline {
  agent none

  stages {
    stage('Test') {
        agent {
            ecs {
                inheritFrom 'my-preconfigured-template'
                cpu 2048
                memory 2048
            }
        }
        steps {
            sh 'echo hello'
        }
    }
  }
}
