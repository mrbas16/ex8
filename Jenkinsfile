properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'dir'
                bat 'python main.py'
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
