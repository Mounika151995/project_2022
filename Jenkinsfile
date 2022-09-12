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
                credentialsId: 'a9ad54ca-67b1-42a9-bb0f-bc6ecf540b8c', 
                url: 'https://github.com/Mounika151995/project_2022.git'
            }
        }    
    }
}