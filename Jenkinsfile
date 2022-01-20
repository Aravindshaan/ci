pipeline {
    agent any
    stages {
        stage('credentials') {
            environment {
                SSH_CREDS = credentials('myfile')
            }
            steps {
                sh 'echo "SSH user is $SSH_CREDS_USR"'
                sh 'echo "SSH passphrase is $SSH_CREDS_PSW"'
            }
        }
    }
}
