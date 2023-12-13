pipeline {
    agent any

   stages{

      stage('git checkout'){

        steps {

           script{
git branch: '*/main', credentialsId: 'jenkins-git', url: 'https://github.com/anilkegarla/myrepo1.git'
           } 
        }
      }


    }
}