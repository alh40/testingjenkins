pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                sh 'python open_file.py'
            }
        }
        stage('Test'){
            steps{
                echo 'Testing..'
            }
        }
    }
}