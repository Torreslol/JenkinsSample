pipeline {
    agent any
    stages {
        stage('Build') {
          sh 'fastlane development_build'
        }
        stage('Test'){
            steps {
                echo 'Testing....'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
