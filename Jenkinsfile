pipeline{
    agent any
    stages{
        stage("Checkout code"){
            steps{
                
                git branch: 'main', credentialsId: 'github_login', url: 'https://github.com/kicku-surya/Project-gradle-CI-CD.git'

            }
        }
        stage("sonar scan"){
            steps{

            echo "sonar need to be integrte"

            }
        }
    }
}