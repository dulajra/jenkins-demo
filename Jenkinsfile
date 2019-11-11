pipeline {
    agent any
    parameters {
        string(name: 'name', description: 'Enter your name please?')
    }
    stages {
        stage('Example') {
            steps {
                echo "${params.name} World!"
            }
        }
    }
}