pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/avitalRubin/docker-demo.git', branch: 'master', credentialsId: 'github-creds', poll: true)
      }
    }

  }
}