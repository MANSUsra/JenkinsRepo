pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }
        stage('Test') {
            steps {
                bat 'java HelloWorld'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Déploiement de l\'application'
            }
        }
    }
}
