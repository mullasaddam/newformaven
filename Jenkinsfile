
pipeline {
    agent any
    environment {
       PATH = "/opt/maven/bin:$PATH"
       }
    stages {
      stage('clean') {
          steps {
            sh "mvn clean"
                }
            }
          stage('install') {
            steps{
             sh "mvn install"
             }
           }

         stage('package') {
          steps {
          sh "mvn package"
          }
         }
  }
 }

