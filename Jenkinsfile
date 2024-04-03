pipeline {
    agent any
    tools {
        nodejs 'nodejs'
    }
 
 
stages {
    stage('Build') {
        steps{
            echo 'Building ...'
            sh 'npm install'
        }
    }
    stage('Test') {
        steps{
            echo 'Testing ...'
            sh 'npm install'
        }
        
    }
    stage('Deploy / Delever') {
        steps{
                echo 'Deploying ...'
 
        }
        
    }
}
}