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
                 echo 'problem1.java'
                }
            }
        }
    }
}
