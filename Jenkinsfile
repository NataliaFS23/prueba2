pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                sh "docker build -t NataliaFS23/pokedex-flask:${env.BUILD_NUMBER} ."
            }
        } 
    }
}
