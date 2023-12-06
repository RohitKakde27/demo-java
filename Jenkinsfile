pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('PULL-PHASE') {
            steps {
                git clone https://github.com/RohitKakde27/demo-java.git
            }
        }
    }
}
