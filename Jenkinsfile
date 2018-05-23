pipeline {
    agent any
    stages {
        stage('Build') {
          steps {
             checkout scm
             sh 'cd ./fastlane'
             sh 'sudo bundle exec fastlane development_build'
          }
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
