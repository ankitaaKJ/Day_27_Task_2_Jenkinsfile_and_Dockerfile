pipeline{
   agent { 
      dockerfile {
         args '-p 1000:80'
      }
   } 
   
   stages {
      stage ('Exec And check website'){
          steps{
            sh 'curl -I http://192.168.0.104:1000/'
          }
      }
  }
   
}
