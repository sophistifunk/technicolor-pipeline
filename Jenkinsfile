pipeline {
    agent any
    stages {
        stage('Without AnsiColor') {
            steps {
                sh 'bash ./ansi.sh'                                
            }
        }               
        stage('With AnsiColor') {
            steps {
                ansiColor('xterm') {
                    sh 'bash ./ansi.sh'
                }                
            }
        }               
    }    
}

