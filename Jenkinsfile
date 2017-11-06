pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'echo $USER' 
            }
        }
    }

    environment {
    	USER = credentials('USER')
    }
}

