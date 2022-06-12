pipeline {
    agent { label 'jenkins-slave-node' }
    stages {
        stage('Build') { 
            steps {
                sh 'printenv' 
                sh 'pwd'
                sh 'whoami'
                echo '$PATH'
                sh 'which npm'
                sh 'ls -al'
                sh 'nodejs -v'
                sh 'npm -v'
                sh 'npm install'    
            }
        }
    }
}
