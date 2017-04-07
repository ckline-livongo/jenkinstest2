pipeline {
  options {
    timestamps()
  }     
    agent { dockerfile true } 
       stages {
         stage('build') {
           steps {
                sh 'java -version'
                sh 'ls -al'
                sh 'docker ps'
           }
         }
       }          
}
