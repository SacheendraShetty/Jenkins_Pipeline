pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh '''
                    ls -lrt
                    pwd
                '''
            }
        }
        stage('Test') { 
            steps {
                sh '''
                    echo "Testing"
                '''                
            }
        }
        stage('Deploy') { 
            steps {
                sh  '''
                    echo "Deploying"
                '''
            }
        }
    }
}