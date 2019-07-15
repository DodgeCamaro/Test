pipeline {
  agent none
  stages {
    stage('Test') {
        agent { label 'ecs'}
        steps {
            sh 'echo hello from ecs'
        }
    }
  }
}
