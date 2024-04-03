pipeline {
    agent any
    stages {
        stage('deploy') {
            steps {
                script {
                    kubernetesDeploy(configs: "deployment.yaml", "service.yaml")
                }
            }
        }
    }
}
