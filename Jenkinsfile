pipeline {
  agent any
  stages {
    stage('listar directorio') {
      parallel {
        stage('listar directorio') {
          steps {
            sh 'pwd && ls -al'
          }
        }

        stage('error') {
          steps {
            sh 'yum install -y apache2'
          }
        }

      }
    }

  }
}