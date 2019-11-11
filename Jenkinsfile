pipeline {
    agent any
    parameters {
        string(name: 'Name', description: 'Enter your name please?')
    }
    stages {
        stage('Example') {
            steps {
                echo "${params.Greeting} World!"
            }
        }
    }
}