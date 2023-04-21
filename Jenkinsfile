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

    }
}