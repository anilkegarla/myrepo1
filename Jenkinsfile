
pipeline {
    agent any

   stages{

    stage('code clone'){

       steps {

           script{
              git branch: 'main', 
              credentialsId: 'git', url: 'https://github.com/anilkegarla/myrepo1.git'
           }}}}}