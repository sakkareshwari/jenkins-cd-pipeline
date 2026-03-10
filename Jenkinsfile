pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Java program'
                bat 'javac welcome.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java welcome'
            }
        }
    }
}
