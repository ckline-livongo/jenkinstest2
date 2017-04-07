pipeline {
  options {
    timestamps()
  }     
    agent { dockerfile true } 
       stages {
         stage('build') {
           steps {
                sh 'sbt about'
           }
         }
       }          
}
