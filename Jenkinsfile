pipeline {
    agent any
    tools {
        nodejs 'NodeJS 18.0.0'
    }
    stages {
        stage('Install') {
            steps {
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
    }
}
