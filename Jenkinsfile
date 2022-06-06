pipeline {
    agent{
        label "demoAgent"
    }

    stages {
        stage('Test') {
            steps {
                echo '다시 테스트'
            }
        }
    }
    post {
        always{
            echo 'pipeline done'
        }
    }
}
