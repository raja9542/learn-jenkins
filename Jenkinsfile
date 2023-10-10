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

pipeline{
    agent any
    stages{

        stage(test1){
            steps{
                script{
                    def.abc="Hello"
                    env.xyz="Hi Raj"

                    print "abc= ${abc}"
                    print "xyz= ${xyz}"
                    print xyz
                }

                script{
                    print xyz
                }
            }
        }
        stage(test2){
            steps{
                script{
                    print xyz
                }
            }
        }

    }
}