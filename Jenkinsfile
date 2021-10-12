pipeline {
    agent any    
    
    stages {
        stage('Build') {
            steps {
                sh'''
                sudo apt install nodejs -S Xenon#flight
                sudo apt install npm -S Xenon#flight
                npm install
                sh''' 
            }
        }
    }
}
