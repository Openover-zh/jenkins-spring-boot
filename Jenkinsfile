pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                //
                sh "java -version"
                sh "git --version"
                sh "mvn -version"
                echo "build"
            }
        }
        stage('Test') {
            steps {
                //
                echo "test"
            }
        }
        stage('Deploy') {
            steps {
                echo "deploy"
            }
        }
    }
}