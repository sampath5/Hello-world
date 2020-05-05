pipeline {
    agent none
    stages {
        stage('build') {
            steps {
                sh 'javac HelloWorld.java'
                sh 'java HelloWorld'
            }
        }
    }
}
