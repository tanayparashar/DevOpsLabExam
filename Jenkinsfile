pipeline {
    agent any
    stages {
        stage('Testing'){
            steps{
                echo 'Running Test'
                bat 'python lab.py'
            }
        }
        stage('Build')
        {
            steps{
                echo 'Buildig jar files...'
            }
        }
    }
}