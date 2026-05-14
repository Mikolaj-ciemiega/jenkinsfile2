pipeline {
    agent any

    tools {
        maven 'M3'
    }

    stages {

        stage('Build') {
            steps {
                dir "mvm clean compile"
            }
        }
        stage('Test') {
                    steps {
                        dir "mvm test"
                    }
                }
    }
}