pipeline {
    agent any

    tools {
        gradle 'Gradle-4.8.1'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building with gradle...'
                sh "gradle install"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
    }
}