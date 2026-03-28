pipeline {
    agent any
    tools {
        nodejs 'NodeJS 6.9.5'
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
