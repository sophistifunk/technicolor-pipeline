pipeline {
    agent any
    stages {
        stage('Colourful logging') {
            steps {
                sh 'echo am here'
                sh 'pwd'
                sh 'ls -al'
                ansiColor('xterm') {
                    sh 'bash ./ansi.sh'
                }                
            }
        }               
    }    
}

