#!groovy
pipeline {
    agent none
   stages {     
    stage('Maven Install') {
      agent {         
       docker {          
         image 'maven:3.3.1'         
     }       
  }       
  steps {
       sh 'mvn clean install'
       }
     }
   }
 }