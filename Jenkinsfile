pipeline {
    agent any

    triggers {
        cron('H/5 * * * *') // Runs every hour; adjust as needed
    }

    stages {
        stage('Simple Cron Job') {
            steps {
                script {
                    echo "Cron job is running!"
                }
            }
        }
    }
}
