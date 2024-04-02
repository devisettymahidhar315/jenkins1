#!/usr/bin/env groovy
pipeline {
    agent any
    stages {
       
        stage("deploy") {
            steps {
                script {
                   
                      
                        sh "kubectl apply -f deploy.yaml"
                        sh "kubectl apply -f ser.yaml"
                    
                }
            }
        }
    }
}
