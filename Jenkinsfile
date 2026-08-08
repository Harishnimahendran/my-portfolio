pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building Portfolio...'
                echo 'HTML, CSS and JavaScript project'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Portfolio...'
                sh 'test -f index.html'
                echo 'Tests passed successfully!'
            }
        }
    }
}