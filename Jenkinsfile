pipeline {
    agent any    
    
    stages {
        stage('Build') {
            steps {
                sh'''
                apt install nodejs -S Xenon#flight
                apt install npm -S Xenon#flight
                npm install
                sh''' 
            }
        }
    }
}
