pipeline {
    agent any

    stages {
        stage('Build project') {
            steps {
                bat 'dotnet build'
            }
        }

        stage('Run dotnet tests') {
            steps {
                bat 'dotnet test'
            }
        }  
    }
}