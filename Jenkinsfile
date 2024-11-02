ipeline {
    agent any
    
    environment {
    PROJECT_NAME = 'Learning od Jenkins'
    MAINTAINER_NAME = 'West Maksim'
    }
    
    stages {
        stage('1-Build'){
            steps{
                echo 'Start build'
                echo 'Building...'
                echo 'End of Build'
            }
        }
        stage('2-Testing') {
            steps{
                echo 'Start build'
                echo 'Testing...'
                echo "Privet ${PROJECT_NAME}"
                echo "Owner is ${MAINTAINER_NAME}"
                echo 'End of Build'}
        }
        stage('2-Deploy') {
            steps{
                echo 'Start Deploy'
                echo 'Building...'
                echo 'End of Deploy'}
    }
    }
    }
