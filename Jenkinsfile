pipeline {
  options {
    timestamps()
  }     
    agent { dockerfile true } 
       stages {
         stage('build') {
           steps {
                sh 'mvn --version'
           }
         }
       }          
}
