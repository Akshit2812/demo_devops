pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat python demo_devops.py
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                bat mvn
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
