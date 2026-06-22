pipeline {
    agent any

    tools {
        maven 'MAVEN_HOME'   // Must match the Maven name configured in Jenkins
    }

    stages {
        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}