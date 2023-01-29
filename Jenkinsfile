@Library('roboshop') _

env.a=10
env.b=15

 pipeline {
   agent {
     label 'workstation'
   }
     stages {
       stage(variable) {
         steps {
           script {
                      echo "a=${a}"
                      echo "b=${b}"
           }
         }
       }
     }
 }
