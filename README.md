# MyJenkins

Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'set'
            }
        }
    }
}
