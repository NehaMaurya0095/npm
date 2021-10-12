pipeline {
    agent any    
    
    stages {
        stage('Build') {
            steps {
                sh'''
                sudo apt install nodejs -A
                sudo apt install npm -A
                npm install
                sh''' 
            }
        }
    }
}
