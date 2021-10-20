pipeline {
    agent any    
    
    stages {
        stage('Build') {
            steps {
                sh'''
                sudo apt install nodej
                sudo apt install npm 
                sudo npm install 
                sh''' 
            }
        }
    }
}
