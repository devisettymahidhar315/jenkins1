pipeline {
    agent any
    stages {
        stage('deploy') {
            steps {
                script {
                    kubernetesDeploy(configs: ["deploy.yaml", "ser.yaml"])
                }
            }
        }
    }
}
