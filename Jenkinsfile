pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'master', url: 'https://github.com/NavyaPatil10/simple-java-maven-app.git'
            }
        }
        stage('Verify') {
            steps {
                echo 'Repository cloned successfully!'
            }
        }
    }
}
