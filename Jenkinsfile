pipeline {
  agent any
      stages {
        stage('First Step') {
          step {
            sh "mvn clean"
          }
        }
        stage('Second Step') {
          step {
            sh "mvn test"
          }
        }
        stage('Third Step') {
          step {
            sh "mvn package"
          }
        }
      }
}
