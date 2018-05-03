pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('sayHello') {
      steps {
        echo 'Hello World!!!'
        sh 'java -version'
      }
    }
  }
}