pipeline {
    agent { docker 'node' } 
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