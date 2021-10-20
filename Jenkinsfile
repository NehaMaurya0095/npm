pipeline {
    agent any    
    
    stages {
        stage('Build') {
            steps {
                sh'''
                sudo apt install nodejs npm -y
                sudo npm install 
                sh''' 
            }
        }
    }
}
