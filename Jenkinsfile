pipeline {
  agent any
      stages {
        stage('First Step') {
          step {
            sh "mvn --version"
          }
        }
        stage('Second Step') {
          step {
            sh "mvn clean"
          }
        }
        stage('Third Step') {
          step {
            sh "mvn test"
          }
        }
      }
}
