pipeline {
  options {
    timestamps()
  }     
  agent { dockerfile {dir 'docker'} } 
       stages {
         stage('build') {
           steps {
                sh 'tcsh'
                sh 'java -version'
                sh 'ls -al'
                sh 'uname -a'
           }
         }
       }          
}
