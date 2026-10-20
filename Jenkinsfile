pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building SmartStock project...'
            }
        }
    }
    post {
        always {
            jiraSendBuildInfo site: 'prathamesh829.atlassian.net'
        }
    }
}
