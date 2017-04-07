pipeline {
  options {
    timestamps()
  }     
    agent { dockerfile true } 
       stages {
         stage('build') {
           steps {
                sh 'ls -al'
                sh 'sbt --version'
           }
         }
       }          
}
