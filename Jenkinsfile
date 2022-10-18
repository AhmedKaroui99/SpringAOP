pipeline {
    agent any

    stages {
        stage('Testing maven') {
            steps {
                sh "mvn -version"
            }
        }
        stage('Testing from git') {
            steps {
                sh "git --version"
            }
        }
    }
}
