pipeline{
    agent any

    stages{
        stage('Verigy Checkout'){
            steps{
                echo 'Jenkins loaded this pipeline from Github'
                bat 'git --version'
                bat 'dir'
                bat 'type README.md'
            }
        }
    }
}