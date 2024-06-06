pipeline {
    agent { label 'raghu' }
    stages {
        stage('test') {
            agent { 
                docker {
                    image 'docker.io/library/alpine:latest'
                }
            }
            steps {
                sh '''
                id 
                ls -althr
                hostname
                cat /etc/os-release
                '''
            }
        }
    }
}
