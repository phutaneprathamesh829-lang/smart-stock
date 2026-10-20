pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'SCRUM-5: Executing SmartStock build pipeline...'
            }
        }
    }
    post {
        always {
            jiraSendBuildInfo site: 'prathamesh829.atlassian.net'
        }
    }
}
