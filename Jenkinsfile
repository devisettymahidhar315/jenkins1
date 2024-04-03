#!/usr/bin/env groovy
pipeline {
    agent {
        docker {
            image 'your-docker-image-with-kubectl-installed'
        }
    }
    stages {
        stage('deploy') {
            steps {
                sh 'kubectl apply -f deploy.yaml'
                sh 'kubectl apply -f ser.yaml'
            }
        }
    }
}

