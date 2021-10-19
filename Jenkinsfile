pipeline {
    agent any
    stages {
        stage('Compile') {
            steps { 
                mvn compile
            }
        }
        stage('test') {
            steps { 
                mvn test
            }
        }
    }
}
