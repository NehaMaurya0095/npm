pipeline {
    agent any    
    
    stages {
        stage('Build') {
            steps {
                sh'''
                apt install nodejs 
                apt install npm 
                npm install
                sh''' 
            }
        }
    }
}
