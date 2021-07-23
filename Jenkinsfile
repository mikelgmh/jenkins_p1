pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '''ls -la
javac src/jenkins_p1/Main.java
java src/jenkins_p1/Main Mikel'''
      }
    }

  }
}