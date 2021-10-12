pipeline {
    agent any    
    
    stages {
        stage('Build') {
            steps {
                sh'''
                sudo apt install nodejs
                sudo apt install npm
                npm install
                sh''' 
            }
        }
    }
}
