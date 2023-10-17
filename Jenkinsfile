pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat "Python ex8.py"
            }
        stage('Hello') {
            steps {
                git 'https://github.com/mrbas16/ex8.git'
                bat "dir"
            }
        }
    }
}
