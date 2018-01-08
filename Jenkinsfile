pipeline {
    agent any
    stages {
        stage('First Stage') {
            steps {
                bat 'mvn compile'
            }
        }
        stage('Test Stage') {
            steps {
                bat 'mvn test'
            }
        }
    }
}
