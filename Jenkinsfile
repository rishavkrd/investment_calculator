
pipeline {
    agent {
    label 'docker' 
  }
    agent { docker
           label 'docker'
           { image 'node:18.16.0-alpine' } 
          }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
