
pipeline {
    agent any
    stages {
      stage('clean') {
          steps {
            sh "mvn clean"
                }
            }
         stage('skiptest') {
            steps {
            sh "-DskipTests"
              }
          }
          stage('install') {
            steps{
             sh "install"
             }
           }

         stage('package') {
          steps {
          sh "package"
          }
         }
  }
 }
