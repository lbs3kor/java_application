pipeline {
    agent any
    environment {
    HTTP_PROXY = 'http://LBS3KOR:Ganesh11223344@rb-proxy-apac.bosch.com:8080'
    HTTPS_PROXY = 'http://LBS3KOR:Ganesh11223344@rb-proxy-apac.bosch.com:8080'
    NO_PROXY = '127.0.0.1,localhost,rb-omscloudasl4.server.bosch.com,127.0.0.*'
}
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

