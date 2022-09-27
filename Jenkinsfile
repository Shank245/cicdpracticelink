pipeline {
    agent any
    tools {
        maven 'maven3'
    }

    stages{
        stage('BUILD'){
            steps{
                sh 'mvn clean package'
            }
        }
    }
}
