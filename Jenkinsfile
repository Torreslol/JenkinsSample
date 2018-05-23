pipeline {
    agent any
    stages {
        stage('Build') {
          steps {
             sh 'export PATH=/usr/local/bin:$PATH'
             sh 'cd ./fastlane'
             sh 'source ~/.bash_profile && bundle exec fastlane development_build'
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
