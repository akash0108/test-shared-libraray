@Library('jenkins-shared@main')_

// library('Jenkins-shared@main')


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
        stage('call the sgared kibrary'){
            steps{
               printMsg()
            }
        }
    }
            
}
    