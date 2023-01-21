pipeline {
    agent any

    stages {
        stage ('Build Image') {
            steps {
                script {
                    dockerapp = docker.build("alespejo/api-produto", '-f ./src/Dockerfile ./src')
                }
            }
        }
    }
}