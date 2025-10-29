pipeline {
    agent any
    triggers {
        cron 'H/15 * * * *' // Triggers every 15 minutes
    }
    stages {
        stage('Scheduled Build') {
            steps {
                echo 'This build was triggered by a schedule.'
            }
        }
    }
}