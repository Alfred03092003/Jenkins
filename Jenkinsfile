pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Alfred03092003/Jenkins.git'
            }
        }

        stage('Build') {
            steps {
                sh '''
                    mkdir -p out
                    javac -d out src/Main.java
                '''
            }
        }

        stage('Run') {
            steps {
                sh 'java -cp out Main'
            }
        }
    }
}

























pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Alfred03092003/Jenkins.git'
            }
        }

        stage('Build') {
            steps {
                bat '''
                if not exist out mkdir out
                javac -d  out src\\Main.java
                '''
            }
        }

        stage('Run') {
            steps {
                sh 'java -cp out Main'
            }
        }
    }
}


















































































































































































































pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // On précise bien la branche main ici
                git branch: 'main', url: 'https://github.com/Alfred03092003/Jenkins.git'
            }
        }

        stage('Build') {
            steps {
                sh '''
                    mkdir -p out
                    javac -d out src/Main.java
                '''
            }
        }

        stage('Run') {
            steps {
                sh 'java -cp out Main'
            }
        }
    }
}pipeline {
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

stage ('Run') {
    steps {
sh 'java -cp out Main'
}
}
}
}


