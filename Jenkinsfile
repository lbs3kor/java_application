pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                script {
                        bat 'mvn clean install -U'  // Windows
                    }
                }
            }
        }
    }

