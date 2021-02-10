pipeline {
    agent any
    stages{
        stage('clone the code') {
            steps {
                git 'https://github.com/himanshurathi/mavenproject'
                sh 'mvn clean package'
            }
       }
    }
}
