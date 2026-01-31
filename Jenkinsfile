pipeline {
    agent any

    tools {
        maven 'Maven-3'
    }

    stages {
        stage('Check Maven') {
            steps {
                sh 'mvn -version'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
