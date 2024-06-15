properties([parameters([booleanParam(description: 'sdfsd', name: 'www')])])
pipeline {
    agent any

    stages {
        stage('Run App') {
            steps {
                sh 'node app.js'
            }
        }
        stage('Testing') {
            steps {
                sh 'node app.js'
            }
        }
    }
}
