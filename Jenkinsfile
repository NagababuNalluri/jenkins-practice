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
            println a
            println b
            }
          script {
          echo "${a}"
          echo "${b}"
          }
         }
       }
     }
 }
