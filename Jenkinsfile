pipeline {
    agent any

    stages{
        stage('Build') {
            steps {
                sh 'cd src && javac com/helloworld/HelloWorld.java'
            }
        }
        stage('Test') {
            steps {
                sh 'cd src && java com.helloworld.HelloWorld'
            }
        }

    }
    
}