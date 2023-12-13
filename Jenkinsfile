pipeline {
    agent any

   stages{

      stage('git checkout'){

        steps {

            git branch: '*/main', credentialsId: 'jenkins-git', url: 'https://github.com/anilkegarla/myrepo1.git'
        }
      }


    }
}