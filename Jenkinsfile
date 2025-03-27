pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'My way to say "Bla ble bli"'
                sh 'du -sch $(pwd)'
                echo 'Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
            }
        }
        stage('run') {
            steps {
                echo 'GTS: Python time!'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
