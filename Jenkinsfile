pipeline {
    agent none
    stages {
        stage('build') {
            steps {
                sh 'javac Helloworld.java'
                sh 'java Helloworld'
            }
        }
    }
}
