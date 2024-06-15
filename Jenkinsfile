properties([parameters([booleanParam(description: 'sdfsd', name: 'www')])])
pipeline {
    agent any

    stages {
        stage('Run App') {
            steps {
                sh 'node app.js'
            }
        }
        stage('Run JavaScript') {
            steps {
                sh 'node app.js'
            }
        }
    }
}
