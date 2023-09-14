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

        stage('') {
          steps {
            sh 'yum install -y apache2'
          }
        }

      }
    }

  }
}