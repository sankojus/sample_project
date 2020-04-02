pipeline {
  agent any
  stages {
    stage('gitclone') {
        steps {
            git branch: 'master', credentialsId: 'git-ss', url: "https://github.com/sankojus/sample_project.git"
          sh "ls -lrth"
          
        } 
    }

    stage('stage2') {
      steps {
        sh """
        touch f1 f2 f3
        ls -lrth
"""
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
