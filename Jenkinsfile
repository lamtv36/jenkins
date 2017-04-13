pipeline {
    agent { docker 'node:latest' } 
    stages {
        stage('Example Build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
            }
        }
    }
}