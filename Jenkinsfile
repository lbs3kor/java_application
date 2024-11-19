pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                script {
                    if (isUnix()) {
                        sh 'mvn -B -DskipTests clean package'  // Linux/MacOS
                    } else {
                        bat 'mvn -B -DskipTests clean package'  // Windows
                    }
                }
            }
        }
    }
}
