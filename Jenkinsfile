pipeline {
    agent{
        label "demoAgent"
    }

    stages('Hello') {
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
