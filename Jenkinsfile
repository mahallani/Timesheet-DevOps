pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/mahallani/Timesheet-DevOps.git'
            }
        }

        stage('Compile') {
            steps {
                sh 'mvn compile'
            }
        }
    }
}
