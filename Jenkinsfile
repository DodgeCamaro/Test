pipeline {
  agent none
  stages {
    stage('Test') {
        agent { label 'ecs-cluster'}
        steps {
            sh 'echo hello from ecs'
        }
    }
  }
}
