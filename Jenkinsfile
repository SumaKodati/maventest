pipeline {
  agent any
      stages {
        stage('First Step') {
          steps {
            sh "mvn clean"
          }
        }
        stage('Second Step') {
          steps {
            sh "mvn test"
          }
        }
        stage('Third Step') {
          steps {
            sh "mvn package"
          }
        }
      }
}
