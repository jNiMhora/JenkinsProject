pipeline {
    agent any
    stages {
        stage('First Stage') {
            steps {
                bat 'mvn -B -DskipTests clean package'
            }
        }
    }
}
