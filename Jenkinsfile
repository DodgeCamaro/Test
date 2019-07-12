agent:
 label: ecs
 dockerImage: maven:3-alpine
 args: -v /tmp:/tmp

stages:
  - name: slave
    agent: slave
    steps:
      - echo "Hello"
