pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/karunakar10000coders/hello1232.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Latest GitHub code downloaded!'
                bat 'dir'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}
