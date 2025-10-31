pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'feature/dev1', url: 'https://github.com/pannalabharathreddy123-maker/bharath-repo.git'
            }
        }
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
            }
        }
    }
}
