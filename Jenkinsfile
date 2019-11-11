pipeline {
    agent any
    parameters {
        string(name: 'userName', defaultValue: 'John', description: 'Enter your name please?')
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