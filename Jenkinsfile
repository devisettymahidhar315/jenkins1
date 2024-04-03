pipeline {
    agent any
    stages {
        stage('deploy') {
           script {
          kubernetesDeploy(configs: "deploy.yaml", "ser.yaml")
        }
        }
    }
}
