/* Requires the Docker Pipeline plugin */
pipeline {
    agent { 
        label 'prod'
        docker { image 'golang:1.22.4-alpine3.20' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
