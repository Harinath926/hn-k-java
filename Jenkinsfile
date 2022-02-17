pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'clone the git repo'
                sh 'pwd'
                sh 'ls -lrt'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}