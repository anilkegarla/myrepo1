

@Library('jenkins_shared_library') _
pipeline {
    
       agent any

   stages{

      stage('Git Checkout') {
            steps {
            vcCheckout(
                branch: "main",
                url: "https://github.com/anilkegarla/myrepo1.git"
            )
            }
    }
            
    }
 }
              
    
    }       
           
           
           