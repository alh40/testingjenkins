pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                sh 'python3 open_file.py'
                // echo 'Building...'
            }
        }
        stage('Test'){
            steps{
                echo 'Testing..'
            }
        }
    }
}