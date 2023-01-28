@Library('roboshop') _

env.a=10
env.b=15
env.name=raj

 pipeline {
   agent {
     label 'workstation'
   }
     stages {
       stage(variable) {
         steps {
          script {
          pv.call()
          pv.add()
          }
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
