pipeline {
    agent any    
    
    stages {
        stage('Build') {
            steps {
                sh'''
                sudo apt install nodejs
                sudo apt install npm 
                sudo npm install 
                sh''' 
            }
        }
    }
}
