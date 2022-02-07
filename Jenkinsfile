pipeline {
    agent any
    
    stages {
        stage('DockerInstall') {
            steps {
                sh 'yum install docker -y'
            }
        }
    }

//     stages {
//         stage('Docker') {
//             steps {
//                 sh 'docker build -t sample .'
//             }
//         }
//     }
}
