pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                // Use bat instead of sh to execute commands in a Windows shell
                bat '"C:\\Program Files\\nodejs\\npm.cmd" install' 
            }
        }
    }
}
