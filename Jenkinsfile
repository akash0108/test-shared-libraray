@Library('Jenkins-shared@feature/tf') _

// TestPipelineSteps(
//     terraformDir: '/tmp'
// )


// properties([
       
// ])

// environment {
//     GOOGLE_APPLICATION_CREDENTIALS = credentials('SA_AUTH')
// }

iacPipeline(
    config =[
        tfDir : '/tmp'
    ],
    gcp_auth = 'SA_AUTH'
)
    


// pipeline{
//     agent any

//     parameters {
//         string(name: 'TestVar', defaultValue: 'Akash parashar', description: 'Value for TestVar')
//     }

//     stages{
//         stage('checkout'){
//             steps{
//                 echo "First job"

//             }
//         }
        
//         stage('build'){
//             steps{
//                echo "Second Stage"
//             }
//         }
//         stage('call the shared kibrary'){
//             steps{
//                printMsg()
//             }
//         }

//         stage('test the script module'){
//             steps{
//                LinuxCMD(params.TestVar)
//             }
//         }
//     }
            
// }




    