pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'echo $HOSTNAME' 
            }
        }
    }

    environment {
    	HOSTNAME = credentials('hostname')
    }
}

