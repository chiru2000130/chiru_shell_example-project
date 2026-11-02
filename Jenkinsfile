
pipeline {
    agent any

    stages {
        stage('Hello Jenkins') {
            steps {
                echo 'Hello Jenkins!'
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
