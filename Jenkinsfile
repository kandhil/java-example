pipeline{
    agent any
    stages{
       stage('Git Checkout Stage'){
            steps{
                git branch: 'main', url: 'https://github.com/sudheer76R/java-example.git'
            }
         }        
       stage('Build Stage'){
            steps{
                sh 'mvn clean install'
            }
         }
    }
}
