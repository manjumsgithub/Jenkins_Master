pipeline {
agent any 
  stages {
      stage ('BUILD')
             {
               steps
               {
                 echo "THIS IS BUILD STAGE"
               }

             }

  stage ('TEST')
             {
               steps
               {
                 echo "THIS IS TEST STAGE"
               }

             }


  stage ('DEPLOY')
             {
               steps
               {
                 echo "THIS IS DEPLOY STAGE"
               }

             }





  stage ('SonarQube')
             {
               steps
               {
                 echo "SonarQube STAGE"
               }

             }

 stage ('parallel job'){
   parallel{
     stage('inside parallel job') {
               steps
               {
                 echo "SonarQube STAGE"
               }

             }
   }
 }











    


}
    }

    











    
             


        
