pipeline {
    agent { label 'raghu' }
    stages {
        stage('test') {
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
