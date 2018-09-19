pipeline {
    agent any 
    // all source and objects will be picked up from the github repo which contains this file
    stages {
        stage('Clean') { 
            steps {
                sh "mvn clean"
                // 
            }
        }
        stage('Maven test command') { 
            steps {
                sh "mvn test"
                // 
            }
        }
        stage('Maven Deploy') { 
            steps {
                   sh "mvn package"
                // 
            }
        }
    }
}
