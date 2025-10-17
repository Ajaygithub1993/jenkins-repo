pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "stage-1"
            }
        }
        stage('Test') { 
            steps {
            echo "stage-2"
            }
        }
        stage('Deploy') { 
            steps {
                sh ''' python3 hello.py
                '''
            }
        }
    }
}
