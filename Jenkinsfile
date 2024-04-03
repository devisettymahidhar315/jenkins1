pipeline {
    agent any
    tools {
        // Define the Kubernetes CLI tool installation
        kubectl 'Kubernetes CLI'
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
