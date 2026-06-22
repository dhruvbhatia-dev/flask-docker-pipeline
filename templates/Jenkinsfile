pipeline {
    agent any
    stages {
        stage("clone code") {
            steps {
                // ye github se code pull krega
                git branch: 'main', url: 'https://github.com/dhruvbhatia-dev/flask-docker-pipeline.git'
            }
        }
        stage('build docker image') {
            steps {
                sh 'docker build -t flask-app:latest .'
            }
        }
        stage('deploy with docker compose') {
            steps {
                // jo purane container h unhe band kro
                sh 'docker compose down'
                //application chalao build image
                sh 'docker compose up -d --build'
            }
        }
    }
}