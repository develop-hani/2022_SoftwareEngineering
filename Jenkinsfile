pipeline {
    agent{
        label "demoAgent"
    }

    stage('Hello') {
            steps {
                echo '202206061741'
            }
    }
    post {
        always{
            echo 'pipeline done'
        }
    }
}
