pipeline {
    agent any
    stages {
        stage('maven install') {
            steps {
                withMaven {
                    bat 'mvn clean install'
                }
            }
        }
    }
}
