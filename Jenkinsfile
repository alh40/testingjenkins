pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                // "C:\Users\gengar\AppData\Local\Programs\python.exe" "Path where your Python script is stored\script a.py"
                bat 'C:\Users\gengar\AppData\Local\Programs\Python\Python310\python.exe open_file.py'
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