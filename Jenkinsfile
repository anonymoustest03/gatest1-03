pipeline {
    agent none
    

    stages {
        
        stage('Run Concurrent Jobs') {
            parallel {
                stage('Job 1') {
                    agent any
                    steps {
                        echo 'Running Job 1'
                        sh 'sleep 25'
                    }
                }
                stage('Job 2') {
                    agent any
                    steps {
                        echo 'Running Job 2'
                        sh 'sleep 25'
                    }
                }
                stage('Job 3') {
                    agent any
                    steps {
                        echo 'Running Job 3'
                        sh 'sleep 25'
                    }
                }
            }
        }
    }
}
