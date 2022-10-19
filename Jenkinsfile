pipeline {
    agent {
        docker {
            image 'node:16.18' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'node -v' 
            }
        }
    }
}