pipeline {
  agent any
  stages {
    stage('slack test') {
      steps {
        slackSend(message: 'this is a test', token: 'TpoLUoJBwuQNWunNDb2ENG1c', teamDomain: 'hotquant', channel: '#project-hq-hqtools')
      }
    }
  }
}