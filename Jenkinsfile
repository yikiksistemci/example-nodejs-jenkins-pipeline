pipeline {
    agent { label 'npm-agent-logan' }
    stages {
        stage('Build') { 
            steps {
                sh 'printenv' 
                sh 'pwd'
                sh 'whoami'
                echo '$PATH'
                sh 'which npm'
                sh 'ls -al'
                sh 'nodejs version'
                sh 'npm version'
                sh 'npm install'    
            }
        }
    }
}
