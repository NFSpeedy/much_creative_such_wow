pipeline {
    agent {
        dockerfile true
    }
    stages {
        stage('Test') {
            steps {
                sh 'python --version'
            }
        }
        stage("Time") {
            steps {
                sh "date"
            }
        }
    }
}