
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // TODO: Add the build command here
                sh './gradlew assemble'
            }
        }
        stage('Test') {
            steps {
                // TODO: Add the test command here
                sh './gradlew test'
            }
        }
        // Add more stages as needed
    }
}

