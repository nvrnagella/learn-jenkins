pipeline{
    agent{
        label 'ansible'
    }
    stages{
        stage('clean jenkins workspace'){
            steps{
                cleanWs()
            }
        }
        stage('Hello'){
            steps{
                echo 'Hello world'
            }
        }
        post{
            always{
                echo "sending an email"
            }
        }

    }
}