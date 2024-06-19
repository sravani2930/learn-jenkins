pipeline {
    agent {
        label 'AGENT-1'
    }
    stages {
        stage('Build') {
            step {
                sh 'echo This is build'
            }
        }    
        stage('Test') {
            step {
                sh 'echo This is Test'
            }
        }
        stage( 'Deploy') {
            step {
                 sh 'echo This is Deploy'
            }
        }
    }    
}