
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Run Python') {
            steps {
                    bat '"C:\\Users\\dhruv\\AppData\\Local\\Python\\pythoncore-3.14-64\\python.exe" app.py'
            }
        }
    }
}
