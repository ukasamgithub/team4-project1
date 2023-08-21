pipeline {
    agent any
    stages{
        stage('1-clone'){
            steps{
                sh "lscpu"
            }
        }
        stage('2-memorycheck'){
            steps{
                sh "free -m"
            }
        }
        stage('3-display'){
            steps{
                sh "cat /etc/passwd"
            }
        }
    }
}