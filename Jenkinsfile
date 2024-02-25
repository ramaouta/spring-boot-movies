pipeline {

    agent {
        label('slave1')
    }
    stages {
        stage('Compile') {
            steps {
                script {
                    sh "mvn clean compile -DskipTests"
                }
            }
        }
        stage('Unit Test') {
            steps {
                script {
                    sh "mvn test"
                }
            }
        }
        stage('package') {
            steps {
                script {
                    sh "mvn package -DskipTests"
                }
            }
        }
        stage('Install') {
            steps {
                script {
                    sh "mvn install"
                }
           }    
        }  
    }
}
