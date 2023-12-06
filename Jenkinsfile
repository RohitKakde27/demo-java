pipeline {
    agent any
    stages {
        stage('PULL-STAGE') {
            steps {
               git credentialsId: '871b9632-60f1-4b32-8a2a-575e0506be4c', url: 'https://github.com/RohitKakde27/demo-java.git'
            }
        }
        stage('BUILD-STAGE') {
            steps {
                sh'mvn clean package'
            }
        }
        stage('TEST') {
            steps {
                echo 'Hello World'
            }
        }
        stage('DEPLOY') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
