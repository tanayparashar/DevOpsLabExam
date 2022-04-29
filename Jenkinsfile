pipeline {
    agent any
    stages {
        stage('Build')
        {
            steps{
                echo 'Running Test'
                bat 'python labExam.py'
            }
        }
    }
}