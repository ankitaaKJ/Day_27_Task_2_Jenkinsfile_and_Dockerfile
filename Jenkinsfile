pipeline{
   agent { 
      dockerfile {
         args '-p 1000:80'
      }
   } 
   
   stages {
      stage ('Exec Test cmd'){
          steps{
            sh 'echo hellooooo'
          }
      }
  }
   
}
