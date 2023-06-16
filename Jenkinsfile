pipeline {
    agent { docker 'node:18.16' }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
                sh 'npm --version'
            }
        }
    }
}
