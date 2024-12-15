@Library('Jenkins-shared@main') _

pipeline{
    agent any


    stages{
        stage('checkout'){
            steps{
                echo "First job"

            }
        }
        
        stage('build'){
            steps{
               echo "Second Stage"
            }
        }
        stage('call the shared kibrary'){
            steps{
               printMsg()
            }
        }

        stage('test the script module'){
            steps{
               LinuxCMD(Akash Parashar)
            }
        }
    }
            
}


// @Library('Jenkins-shared@main') _

// pipeline {
//     agent any
//     stages {
//         stage('Test Library') {
//             steps {
//                 script {
//                     printMsg()
//                 }
//             }
//         }
//     }
// }

    