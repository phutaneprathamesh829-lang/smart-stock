pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'SCRUM-5: Building SmartStock project for Jira traceability'
            }
        }
    }
    post {
        always {
            jiraSendBuildInfo site: 'prathamesh829.atlassian.net'
        }
    }
}
