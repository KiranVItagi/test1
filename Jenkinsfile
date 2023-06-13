pipeline {
    agent { label 'slave1' } 
    stages {
        stage('checkout1') {
            steps {
                sh 'echo checkout1 step'
            }
        }
        stage('checkout2') {
            steps {
                sh 'echo checkout2 step'
            }
        }
        stage('checkout3') {
            steps {
                sh 'echo checkout3 step'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
