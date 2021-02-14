pipeline {
    agent any

    stages {
        stage('clone and clean') {
            steps {
                sh "pwd"
               
                sh "mvn clean"
                sh "pwd"
            }
        }
          stage('Test') {
            steps {
                
                sh "mvn test"
                
            }
        }
          stage('Package') {
            steps {
             
                sh "mvn package"
                
            }
        }
    }
}
