pipeline {
  agent any
  stages {
    stage('Get code') {
      agent any
      steps {
        git(url: 'https://github.com/H-HABIBALLAH/first-project-linked-to-jenkins-server.git', branch: 'dev')
      }
    }

  }
}