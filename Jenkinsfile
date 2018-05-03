pipeline {
  agent {
    label 'jdk8'
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