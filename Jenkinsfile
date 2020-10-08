pipeline {
    agent { label 'npm-agent' }
    
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}