pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/JeremyKomarov/runJavaScript.git'                
                sh 'ls -ltr'
            }
        }
    }.
}
