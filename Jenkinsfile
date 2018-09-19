pipeline {
    agent any 
    stages {
        stage('Clean') { 
            steps {
                sh "mvn clean -f my-app"
                // 
            }
        }
        stage('Maven test command') { 
            steps {
                sh "mvn test -f my-app"
                // 
            }
        }
        stage('Maven Deploy') { 
            steps {
                   sh "mvn package -f my-app"
                // 
            }
        }
    }
}
