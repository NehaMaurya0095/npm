pipeline {
    agent any    
    
    stages {
        stage('Build') {
            steps {
                sh'''
                sudo apt install nodejs -S @Xenonstack#12 
                sudo apt install npm -S @Xenonstack#12
                sudo npm install -S @Xenonstack#12
                sh''' 
            }
        }
    }
}
