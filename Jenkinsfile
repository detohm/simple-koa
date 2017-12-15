pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        sh '''scp -r . jenkins@10.0.0.5:/var/www/
'''
      }
    }
  }
}