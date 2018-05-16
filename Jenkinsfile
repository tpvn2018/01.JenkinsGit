pipeline {
    agent { docker { image 'maven:3.5.3' } }
    stages {
        stage('build') {
            steps {
               bat 'javac hello.java'
            }
        }
    }
}