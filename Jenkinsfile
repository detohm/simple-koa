pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        sh '''scp . root@staging:/var/www/
'''
      }
    }
  }
}