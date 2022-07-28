pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                sh 'python open_file.py'
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