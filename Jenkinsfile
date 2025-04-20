pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                sshagent(['ssh_key_for_git']) {
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
