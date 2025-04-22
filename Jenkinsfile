pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                echo 'Just a simple build step'
                sh 'cat hello.txt'
            }
        }
        stage('Done') {
            steps {
                echo 'Build complete'
            }
        }
    }
}