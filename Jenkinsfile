pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Website Project...'
                // Run the build steps (e.g., shell script, npm build)
                sh './hello.sh' // Replace with your actual build script if needed
            }
        }

        stage('Test') {
            steps {
                echo 'Running Tests...'
                // Run your test scripts (if any)
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Website...'
                // Add your deployment steps here (e.g., copying files, starting servers)
            }
        }
    }
}
