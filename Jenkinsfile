pipeline {
    agent any    
    
    stages {
        stage('Build') {
            steps {
                sudo apt install nodejs
                sudo apt install npm
                sh 'npm install'
            }
        }
    }
}
