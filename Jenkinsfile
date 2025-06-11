pipeline {
    agent any

    parameters {
        string(name: 'USERNAME', defaultValue: 'guest', description: 'Enter your name')
    }

    stages {
        stage('Greet User') {
            steps {
                echo "Hello, ${params.USERNAME}!"
            }
        }
    }
}
