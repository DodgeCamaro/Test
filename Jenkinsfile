pipeline {
  agent none

  stages {
    stage('Test') {
        agent {
            ecs {
                cloud 'ecs-cloud'
                inheritFrom 'base'
                cpu 1024
                memory 2048
            }
        }
        steps {
            sh 'echo hello'
        }
    }
  }
}
