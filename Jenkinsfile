//pipeline{
//
// agent {
//     label 'ansible'
// }
//
// stages{
//
//   stage('Hello World1'){
//
//     steps{
//       echo "hello world"
//     }
//   }
//
//     stage('Hello World2'){
//         steps{
//             echo "hello world"
//         }
//     }
//
//     stage('Hello World3'){
//         steps{
//             echo "hello world"
//         }
//     }
// }
//
// post{
//     always{
//         echo "Send Email"
//     }
//     changed{
//         echo "something"
//     }
// }
//}

@Library('roboshop') _

pipeline {
  agent any
   stages {
       stage('test1'){
           steps{
               script{
                   env.abc="Hello"
                   def xyz=10
                   print "abc= ${abc}"
                   print "xyz= ${xyz}"
                   print abc
               }
               script{
                   print abc

               }
           }
       }
       stage('test2'){
           steps{
               script{
                   print abc
               }
           }
       }
   }
}
