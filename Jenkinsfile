pipeline {
  agent any

  tools {nodejs "nodejs"}

  stages {

    stage('Git') {
      steps {
        git 'https://github.com/Nandhini-16/samplenode.git'
      }
    }

    stage('Build') {
      steps {
        sh 'npm install'
      }
    }  


    stage('Test') {
      steps {
        sh 'node test'
      }
    }
  }
}
