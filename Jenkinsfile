pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }
        stage('Test') {
            steps {
                sh 'java HelloWorld'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Déploiement de l\'application'
            }
        }
    }
}
