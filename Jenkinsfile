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
            sh "mvn -DskipTests"
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


