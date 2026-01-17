pipeline {

  agent any

  stages{

    stage("BUILD")
    {
      steps {
           echo 'BUILD  - Amar Stage'
          
        script {
                     def test = 2+2 > 3 ? 'cool correct' : 'not cool correct 1'  
          }
      }    
     
    }

     stage("TEST Amar Stage")
    {
      steps {
                   echo 'TEST Amar Stage'
      
      }    
      
    }


     stage("DEPLOY Amar Stage")
    {
      steps {
           echo 'DEPLOY Amar Stage'
      
      }    
      
    }
  }
}
