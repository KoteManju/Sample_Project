pipeline {
    
    agent any
    
    stages{
        
        stage('fetch code'){
            steps{
                git branch: 'python', url: 'https://github.com/KoteManju/Sample_Project.git' 
            }
        }
        
        stage('build'){
            steps{
                sh 'python3 list_akanksha.py'
            }
        }
    }
}
