pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application'
            }
        }

       stage('Test') {
        steps {
            echo 'Running tests'
        }
    }

    stage('Docker Check') {
        steps {
            sh 'docker --version'
        }
    }
        
stage('Docker Build') {
    steps {
        sh 'docker build -t devops-nginx .'
    }
}
        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}
