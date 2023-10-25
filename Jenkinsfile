pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                sh "docker build -t nataliafs23/pokedex-flask:${env.BUILD_NUMBER} ."
            }
        } 
    }
}
