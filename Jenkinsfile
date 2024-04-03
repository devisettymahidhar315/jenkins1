pipeline {
    agent any

    stages {
        stage('deploy') {
            steps {
                script {
                    sh "kubectl apply -f deploy.yaml"
                }
            }
        }
    }
}
