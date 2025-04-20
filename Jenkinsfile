pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', credentialsId: 'ssh_key_for_git', url: 'git@github.com:kain3x6/html-page.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}
