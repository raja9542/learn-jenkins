pipeline{

 agent {
     label 'ansible'
 }

 stages{
     addBadge icon: 'text.gif', id: '', link: '', text: 'github'
   stage('Hello World1'){
     steps{
       echo "hello world"
     }
   }

     stage('Hello World2'){
         steps{
             echo "hello world"
         }
     }

     stage('Hello World3'){
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