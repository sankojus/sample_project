pipeline {
  agent any
  stages {
    stage('gitclone') {
        steps {
            git branch: 'master', credentialsId: 'git-ss', url: "https://github.com/sankojus/sample_project.git"
          sh "ls -lrth"
          sh "touch f1 f2 f3"
        }
    }

    stage('stage2') {
      steps {
        sh '''echo "hello"
'''
      }
    }
    stage('satge3') {
    steps{
      sh '''
      echo my first pipeline is success
'''
    }
    }

  }
}
