pipeline {
    agent {
        node {
            label 'docker-agent-python'
        }
    }
    triggers {
        pollSCM '* * * * *'
    }
    stages {
        stage('Build') {
            steps {
                echo "Building..."
                sh '''
                echo "Doing build stuff..."
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing..."
                sh '''
                echo "Doing test stuff..."
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo "Testing..."
                sh '''
                echo "Doing delivering stuff..."
                '''
            }    
        }
    }
}
