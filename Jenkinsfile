
pipeline {
    agent any

   stages{

      stage('Git Checkout') {
            steps {
            vcCheckout(
                branch: "main",
                url: "https://github.com/nclouds/jenkins_shared_library"
            )
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