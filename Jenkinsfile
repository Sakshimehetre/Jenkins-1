pipeline {
    agent any
    stages {
        stage('compile') {
            steps {
                sh 'make all'
                echo "compiled"
            }
        }
    }
}
