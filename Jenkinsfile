pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        bat '%M2_HOME%\\bin\\mvn test'
      }
    }
    stage('install') {
      steps {
        bat 'C:\\Users\\georgiad\\Desktop\\New folder\\apache-maven-3.5.2\\bin\\mvn install'
      }
    }
  }
}