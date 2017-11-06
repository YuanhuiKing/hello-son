pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'echo hostname' 
            }
        }
    }

    environment {
    	HOSTNAME = credentials('hostname')
    }
}

