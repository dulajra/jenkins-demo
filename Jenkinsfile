pipeline {
    agent any
    properties([
            parameters {
                string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
            }
    ])
    stages {
        stage('Example') {
            steps {
                echo "${params.Greeting} World!"
            }
        }
    }
}