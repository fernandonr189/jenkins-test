/* Requires the Docker Pipeline plugin */
pipeline {
    agent { prod { image 'golang:1.22.4-alpine3.20' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
