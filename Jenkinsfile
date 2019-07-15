pipeline {
  agent none

  stages {
    stage('Test') {
        agent {
            ecs {
                inheritFrom 'jnlp-slave'
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
