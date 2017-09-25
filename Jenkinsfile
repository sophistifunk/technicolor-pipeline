pipeline {
    agent any
    stages {
        stage('Without AnsiColor') {
            steps {
                println 'About to run without the AnsiColor wrapper'
                sh 'bash ./ansi.sh'                                
            }
        } 
        /*
        stage('With AnsiColor') {
            steps {
                println 'About to attempt running in the AnsiColor wrapper'
                ansiColor('xterm') {
                    sh 'bash ./ansi.sh'
                }                
            }
        }               
        */
    }    
}

