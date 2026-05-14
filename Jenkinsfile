pipeline {
    agent any

    tools {
        maven 'M3'
    }

    stages {

        stage('Build') {
            steps {
            sh "mvm clean compile"
            }
        }
        stage('Test') {
            steps {
            sh "mvm test"
            }
        }
    }
}