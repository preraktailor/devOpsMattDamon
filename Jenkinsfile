pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                echo 'Getting source code from Github'
            }
        }
        stage('Build'){
            steps{
                echo 'Building the project'
            }
        }
        stage('Test'){
            steps{
                echo 'Testing the project'
            }
        }
        stage('Deploy'){
            steps{
                echo 'Deploying the project'
            }
        }
    }
    post{
        success{
            echo 'Pipeline completed successfully!'
        }
        failure{
            echo 'pipeline failed!'
        }
    }
}