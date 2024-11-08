pipeline {
    agent any
    stages{
        stage("Git Checkout"){
            steps{
                git 'https://github.com/Vineeth8686/counter-app.git'
            }
        }
        stage("Unit Testing"){
            steps{
                sh 'mvn test'
            }
        }
    }
}