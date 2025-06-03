pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/haroon6148/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building..."'
            }
        }

       stage('Deploy') {
    steps {
        sh 'echo "Deploying..."'
        sh 'mkdir -p $HOME/deploy'
        sh 'cp index.html $HOME/deploy/'
    }
}

    }
}
