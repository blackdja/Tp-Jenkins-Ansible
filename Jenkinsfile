pipeline {
        agent {
                docker {
                        image 'node:6-alpine'       
                }
        }

        stages {
                stage('Build and test') {
                        steps {
                                sh 'npm install'
                                sh 'npm test'
                        }
                }
        }
}