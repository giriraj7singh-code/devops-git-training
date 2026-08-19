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

        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}
