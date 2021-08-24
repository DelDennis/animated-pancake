pipeline {
    agent any
    stages {
        
        stage('Clone git repo') {
            steps {
                sh 'echo "STAGE 1: Cloning app code from SCM ..."'
            }    

        stage('Unit Tests') {
            steps {
                sh 'echo "STAGE 2: Running unit tests ..."'
            }    
   

        stage('Buildcheck') {
            steps {
                sh 'echo "STAGE 3: Initiating codebuild job ..."'
            }    
    }   
}
