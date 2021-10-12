pipeline {
    agent any    
    
    stages {
        stage('Build') {
            steps {
                sh'''
                ls
                mkdir test
                cd test
                touch abc
                sh''' 
            }
        }
    }
}
