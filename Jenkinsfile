pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Calculator Application'
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Calculator Application'
                sh 'test -f index.html'
                echo 'Calculator Application Test Successful'
            }
        }
    }
}
