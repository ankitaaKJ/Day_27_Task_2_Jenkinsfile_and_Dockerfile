pipeline{
   agent { 
      dockerfile {
         args '-p 1000:80'
      }
   } 
   
   stages {
      stage ('Exec And check website'){
          steps{
            sh 'ip addr show'
          }
      }
  }
   
}
