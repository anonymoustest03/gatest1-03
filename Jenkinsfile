pipeline { 
    agent none  // No global agent

    stages {
        stage('Run stress on multiple Docker containers') {
            parallel {
                stage('Run stress on Docker 1') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'  // Use a base image
                            args '-u root'  // Ensure root privileges for installation
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 2') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 3') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                // Repeat for Docker 4 to Docker 19...
                stage('Run stress on Docker 4') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 5') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 6') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 7') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 8') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 9') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 10') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 11') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 12') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 13') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 14') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 15') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 16') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 17') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 18') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
                stage('Run stress on Docker 19') {
                    agent {
                        docker {
                            image 'ubuntu:20.04'
                            args '-u root'
                        }
                    }
                    steps {
                        sh '''
                          apt-get update && apt-get install -y stress
                          stress --cpu 32 --timeout 1800s
                        '''
                    }
                }
            }
        }
    }
}
