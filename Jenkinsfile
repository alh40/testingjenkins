pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                sh 'py open_file.py'
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