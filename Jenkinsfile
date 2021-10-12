pipeline {
    agent any    
    
    stages {
        stage('Build') {
            steps {
                apt install nodejs
                apt install npm
                sh 'npm install'
            }
        }
    
