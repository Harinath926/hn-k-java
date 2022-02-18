pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'clone the git repo'
                sh 'terraform init'
                sh 'terraform plan'
            }
        }
        stage('Test') {
            steps {
                echo 'terraform apply'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}