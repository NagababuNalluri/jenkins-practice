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
            println value of a
            println value of b
            }
          script {
          echo "${a}"
          echo "${b}"
          }
         }
       }
     }
 }
