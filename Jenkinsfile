pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo "Building"
            }
        }
        stage('Test'){
            steps{
                echo "Testing"
            }
        }
        stage('Deploy'){
            steps{
                echo "Deploying"
            }
        }
        stage('checkout'){
            steps{
                git branch: 'Master', 
                credentialsId: 'fda2e913-0d81-42b3-a348-73d2655fbb77', 
                url: 'https://github.com/Mounika151995/project_2022.git'
            }
        }    
    }
}