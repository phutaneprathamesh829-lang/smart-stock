pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building SmartStock project...'
            }
        }
        stage('Notify Jira') {
            steps {
                jiraSendBuildInfo site: 'phutaneprathamesh829.atlassian.net', credentialsId: 'jira-api-token'
            }
        }
    }
}
