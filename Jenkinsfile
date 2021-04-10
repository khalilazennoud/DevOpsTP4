pipeline {
  agent any
   tools { 
        maven 'Maven3' 
      
    }
  stages {
    stage('Clean'){
      steps{
        sh 'mvn clean install'
      }
    
    }
  }
}
