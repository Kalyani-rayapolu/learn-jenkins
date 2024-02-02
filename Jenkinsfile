pipeline {
    agent {
        node {
            label 'AGENT-1'
        }
    }
    environment { 
        GREETING = 'Hello Jenkins'
    }
    // build
        stages {
            stage('Build') {
                steps {
                    echo 'Building..'
                }
            }
            stage('Test') {
                steps {
                    echo 'Testing..'
                }
            }
            stage('Deploy') {
                steps {
                    echo 'Deploying..'
                }
            }

        }
}