pipeline{
    agent any
    stages{
        stage('Checkout') {
            steps {
                
                git branch: 'main', url: 'https://github.com/KeerthuK29/MyNewRepo.git/'
            }
        }
        stage('Build'){
            steps{
                script {
                  bat 'javac problem1.java'
                }
            }
        }
        stage('Run'){
            steps{
                script{
                    bat 'java problem1'
                }
            }
        }
    }
}
