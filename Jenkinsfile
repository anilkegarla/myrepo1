
pipeline {
    agent any

   stages{

    stage('code clone'){

       steps {

           script{
              git branch: 'main', 
              credentialsId: 'git', url: 'https://github.com/anilkegarla/myrepo1.git'
           }
             }
              }
           
    stage('unit test'){
      steps{
        sh 'mvn test'
        }
     
    }
           
    stage('Integration test'){
      steps  {
        sh 'mvn verify -DskipUnitTests'
      } 
    }

    stage('maven build'){
      steps{
        sh 'mvn clean install'
      }
    }       
           
           }
           }