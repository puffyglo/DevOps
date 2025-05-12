pipeline {
    agent any

    stages {
        stage('Clone External Repo and List Files') {
            steps {
                git branch: 'main', url: 'https://github.com/puffyglo/DevOps.git'
                sh '''
                    ls -la
                '''
            }
        }
    }
}
