
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
     stage('maven build'){

       steps{

         sh  'mvn package'

  }
}  
     stage('maven test'){

     steps{
      sh 'mvn test'
     }
     }

    }
}