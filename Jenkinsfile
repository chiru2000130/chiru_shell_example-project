

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Source code checkout complete'
            }
        }

        stage('HTML Validation') {
            steps {
                sh 'test -f index.html'
                echo 'HTML file exists!'
            }
        }

        stage('Docker Test') {
            steps {
                sh 'docker --version'
                sh 'docker run --rm hello-world'
            }
        }
    }
}

