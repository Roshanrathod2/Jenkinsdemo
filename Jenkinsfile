Pipeline{
    agent any{
        stages{
            stage('Checkout code'){
                steps{
                    Checkout scm
                }
                stage('Run extract.py'){
                    steps{
                        bat "C:\\Users\\Roshan Rathod\\AppData\\Local\\Microsoft\\WindowsApps\\python.exe extract.py"
                    }
                }

            }
        }
    }
}