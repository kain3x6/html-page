pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                sshagent(['github-ssh-key']) {
                    git 'git@github.com:kain3x6/html-page.git'
                }
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}
