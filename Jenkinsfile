pipeline {
    agent any
    stages {
        stage('Without AnsiColor') {
            steps {
                println 'About to run without the AnsiColor wrapper'
                sh 'bash ./ansi.sh'                                
            }
        } 
        stage('Stupid-long step name') {
            steps {
                sh 'echo This https://en.wikipedia.org/wiki/Label is long. You just won\'t believe how vastly hugely mindbogglingly long it is. I mean you may think it\'s a long way down the road to the chemist\'s, but that\'s just peanuts to this title.'
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

