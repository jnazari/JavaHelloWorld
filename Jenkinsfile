pipeline {
    agent any 
    stages {
        stage('---date and time---') { 
            steps {
                sh "date"
                sh "time"
            }
        }
        stage('compile') { 
            steps {
                sh "javac HelloWorld.java"
            }
        }
        stage('run') { 
            steps {
                sh "java HelloWorld"
            }
        }
    }
}

