properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'dir'
            }
        }
        stage('Buy') {
            steps {
                bat 'dir'
                bat 'time /t'
            }
        }        
    }
}
