pipeline {
    agent any
    stages {
        stage ('Clone') {
            steps {
                git branch: 'main', credentialsId: 'global', url: 'https://github.com/vohoang17-99/jenkins-github2.git'
        }
    }
}
