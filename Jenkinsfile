pipeline {
    agent any

    stages {
        stage('Hello World') {
            steps {
                echo 'Hello World'
            }
        }
        stage('run script') {
            steps {
                sh'''
                chmod +x hello.sh
                ./hello.sh
                '''     
            }
        }
    }
}
