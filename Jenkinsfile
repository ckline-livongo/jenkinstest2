pipeline {
  options {
    timestamps()
  }     
  agent { dockerfile {dir 'docker'} } 
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
