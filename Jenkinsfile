pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                // "C:\Users\gengar\AppData\Local\Programs\python.exe" "Path where your Python script is stored\script a.py"
                bat 'py open_file.py' 
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