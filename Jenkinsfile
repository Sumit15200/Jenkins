pipeline{
       
       agent any

       stages{
     
            stage('Compile'){

               steps{
                       sh 'javac JavaApp'

               }



            }
              stage("Run"){

               steps{
                       sh 'java JavaApp.java'

               }



            }

       }





}