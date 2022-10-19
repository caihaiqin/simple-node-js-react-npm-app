pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'docker ps' 
                sh 'npm install' 
            }
        }
    }
}