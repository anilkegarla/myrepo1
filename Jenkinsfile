

@Library('jenkins_shared_library') _
pipeline {
    
       agent any

   stages{
      
      stage("gitcheckout"){
         
          steps{
           git branch: 'main', url: 'https://github.com/anilkegarla/myrepo1.git'
   
         }

      }
      stage ('maven build'){

         steps {

            mvnBuild()
        }
      }


    }
 }
              
    
    
           
           
           