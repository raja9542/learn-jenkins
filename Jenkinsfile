pipeline{

 agent {
     label 'ansible'
 }

 stages{

   stage('Hello World'){
     steps{
       echo "hello world"
     }
   }
 }

 post{
     always{
         echo "Send Email"
     }
     changed{
         echo "something"
     }
 }
}