pipeline {
    agent any
    parameters {
        string(name: 'userName', description: 'Enter your name please?')
    }
    stages {
        stage('Example') {
            steps {
                echo "${params.userName} World!"
            }
        }
    }
}