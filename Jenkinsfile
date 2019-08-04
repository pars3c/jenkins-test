pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                python test.py
            }
        }
        stage('Test') {
            steps {
                echo 'Testing.. Aderito'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.... Aderito 2'
            }
        }
    }
}
