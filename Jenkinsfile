pipeline {
    agent { label 'npm-agent-logan' }
    stages {
        stage('Build') { 
            steps {
                sh 'printenv && pwd && whoami && echo $PATH && which npm && ls -al',
                sh 'npm install'    
            }
        }
    }
}
