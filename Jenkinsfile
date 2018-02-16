pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        bat '"C:\\Users\\georgiad\\Desktop\\New folder\\apache-maven-3.5.2\\bin\\mvn.cmd" test'
      }
    }
    stage('install') {
      steps {
        bat 'C:\\Users\\georgiad\\Desktop\\New folder\\apache-maven-3.5.2\\bin\\mvn install'
      }
    }
  }
}