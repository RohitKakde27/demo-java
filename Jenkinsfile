pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('PULL-PHASE') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
