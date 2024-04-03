#!/usr/bin/env groovy
pipeline {
   agent any
    stages {
        stage('deploy') {
            steps {
                sh 'kubectl apply -f deploy.yaml'
                sh 'kubectl apply -f ser.yaml'
            }
        }
    }
}

