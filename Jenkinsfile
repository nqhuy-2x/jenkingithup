pipeline {
    agent any
    stages {
        stage('Clone'){
            steps{
                git 'https://github.com/nqhuy-2x/jenkingithup.git'
            }
        }
        stage("Build") {
            steps {
                echo "Build stage."                
            }
        }
        stage("Test") {
            steps {
                echo "Test stage."
            }
        }
        stage("Release") {
            steps {
                echo "Release stage."
            }
        }
    }
}