pipeline {

    agent any


    stages {


      stage('build clean') {

          steps {
            sh 'clean'

            }

         }

         stage('skiptest') {

            steps {

            sh '-DskipTests'

            }

          }

          stage('install') {

            steps{

             sh 'install'

             }
           }

         stage('package') {

          steps {

          sh 'package'

          }

         }
 }
 }
