pipeline {
    agent {
        docker {
            image 'node:latest'
            label 'nodejs'
        }
    } 
    stages {
        stage('Example Build') {
            steps {
                echo "npm install "
                sh 'npm install'
                echo "npm install done"
                sh 'npm run build'
            }
        }
    }
}