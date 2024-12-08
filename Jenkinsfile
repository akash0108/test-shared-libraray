@Library('jenkins-shared@main') _


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
    }
            
}
    