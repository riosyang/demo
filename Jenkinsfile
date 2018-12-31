pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        git(url: 'git@47.105.245.184:root/demo.git', branch: 'master')
      }
    }
    stage('mvn') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}