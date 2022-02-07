pipeline {
    agent any
    
    stages {
        stage('DockerInstall') {
            steps {
                sh 'sudo apt-get install docker -y'
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
