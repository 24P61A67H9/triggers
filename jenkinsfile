pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'YOUR-GITHUB-URL'
            }
        }

        stage('Run Script') {
            steps {
                bat 'python test.py'
            }
        }
    }
}
