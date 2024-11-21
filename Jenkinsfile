pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                script {
                        bat 'mvn -B -DskipTests clean package'  // Windows
                    }
                }
            }
        }
    }

