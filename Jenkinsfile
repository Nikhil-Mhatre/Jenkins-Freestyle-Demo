pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'This is the Build stage.'
                echo "Running on agent: $NODE_NAME"
            }
        }
        stage('Test') {
            steps {
                echo 'This is the Test stage.'
                echo "Job: $JOB_NAME, Build: $BUILD_NUMBER"
            }
        }
        stage('Deploy') {
            steps {
                echo 'This is the Deploy stage.'
                echo 'Deploying to production (not really!)'
            }
        }
    }
}
