pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh '''#!/bin/bash

                    python test.py
                '''
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
