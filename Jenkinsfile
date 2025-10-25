pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'master', url: 'https://github.com/NavyaPatil10/simple-java-maven-app.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Simulating build stage...'
            }
        }
        stage('Test') {
            steps {
                echo 'Simulating test stage...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Simulating deployment...'
            }
        }
    }
}
