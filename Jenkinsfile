@Library('roboshop') _

ci()

 pipeline {
   agent {
     label 'workstation'
   }
     stages {
       stage(variable) {
         steps {
          script{
          pv.call('raj')
          pv.add(1,2)
          }
         }
       }
     }
 }