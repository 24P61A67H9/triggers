pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/24P61A67H9/triggers.git'
            }
        }

        stage('Run Script') {
            steps {
                sh 'python3 test.py'
            }
        }
    }
}
