pipeline {

  agent any
  
  stages{
    stage ('Build'){
      steps{
        echo "Builing the project"
        
    }
  }
    post{
      success{
        emailext body: 'Email sent out from Jenkins', subject: 'Test Email', to: 'bindurs.117@gmail.com'
        
      }
    }
  }

