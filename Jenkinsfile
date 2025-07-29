pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Alfred03092003/Jenkins.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mkdir -p out && javac -d out src/Main.java'
            }
        }

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Alfred03092003/Jenkins.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mkdir -p out && javac -d out src/Main.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java -cp out Main'
            }
        stage('Run') {
            steps {
                sh 'java -cp out Main'
            }
        }
    }
}
