pipeline {
    agent any
    
    stages {
        stage('DockerInstall') {
            steps {
                sh 'apt-get update -y'
                sh 'apt-get install docker -y'
            }
        }
    }
        stage('Docker') {
            steps {
                sh 'docker build -t sample .'
            }
        }
    }
