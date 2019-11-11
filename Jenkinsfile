pipeline {
    agent any
    parameters {
        string(name: 'userName', description: 'Enter your name please?')
    }
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.userName}!"
                sh 'java -version'
            }
        }
    }
}