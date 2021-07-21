pipeline {
    agent any 
    environment {
        demovar = 'demovalue'
    }
    stages {
        stage('clone the code') {
            steps {
                sh 'echo "i am cloning the code"'
            }
        }
        stage('build') {
            steps {
                sh 'echo "i am doing the build"'
            }
        }
        stage('deploy') {
            steps {
                sh 'echo "i am deploying"'
            }
        }
        stage('approve') {
            steps {
                input 'Approved by manager'
            }
        }
        stage('prod deployment') {
            steps {
                sh 'echo "i am prod deploying"'
            }
        }
    }
}
