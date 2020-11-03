pipeline {
    agent { label 'npm-agent-logan' }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
