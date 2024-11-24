#!/usr/bin/env groovy
@Library('jenkins-shared')_


pipeline{
      agent any 

      def gv

     stages {
        stage("init") {
            steps {
                script {
                    gv = load "script.groovy"
                }
            }
        }
        stage("build jar") {
            steps {
                script {
                    printMsg()
                }
            }
        }
     }  

}