pipeline {
    agent { label 'slave1' } 
    stages {
        stage('checkout') {
            steps {
                sh 'echo checkout step'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
