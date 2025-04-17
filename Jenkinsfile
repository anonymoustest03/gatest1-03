pipeline {
    agent any

    stages {
        stage('Run Concurrent Jobs') {
            parallel {
                stage('Job 1') {
                    steps {
                        echo 'Running Job 1'
                        sh 'sleep 25'
                    }
                }
                stage('Job 2') {
                    steps {
                        echo 'Running Job 2'
                        sh 'sleep 25'
                    }
                }
                stage('Job 3') {
                    steps {
                        echo 'Running Job 3'
                        sh 'sleep 25'
                    }
                }
            }
        }
    }
}
