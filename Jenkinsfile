pipeline {
    agent any

    stages{
        stage('Build') {
            steps {
                sh 'cd src'
                sh 'javac com/helloworld/HelloWorld.java'
            }
        }
        stage('Test') {
            steps {
                sh 'cd src'
                sh 'java com.helloworld.HelloWorld'
            }
        }

    }
    
}