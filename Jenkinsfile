pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Welcome to Jenkins World'
                sh 'date'
                sh 'python --version'
                sh 'python pipeline.py'
                sh 'pwd'
            }
        }
    }
}
