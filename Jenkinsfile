pipeline {
    agent { label 'npm-agent-logan' }
    stages {
        stage('Build') { 
            steps {
                sh 'printenv' 
                sh 'pwd'
                sh 'whoami'
                echo '$PATH'
                which npm
                sh 'ls -al'
                sh 'npm install'    
            }
        }
    }
}
