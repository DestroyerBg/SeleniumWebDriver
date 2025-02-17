pipeline {
    agent any
     stages {
        stage('Build app') {
            steps {
                bat 'dotnet build'
            }
        }
        stage('Test app') {
            steps {
                bat 'dotnet test'
            }
        }
    }
}