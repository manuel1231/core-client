pipeline {
    agent any
    tools { nodejs "NodeJS" }
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/manuel1231/core-client.git'
                nodejs() {
                  sh 'npm install'
                }
            }
        }
    }
}
