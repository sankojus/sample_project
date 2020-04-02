pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        sh ''' 
        pwd
        ls -lrth
        
        '''
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
