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
                sh 'npm -v'
                sh 'npm install' 
                sh 'ls -la'
            }
        }
    }
}
