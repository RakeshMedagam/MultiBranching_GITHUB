pipeline {
    agent any

    stages {
        stage('production branch') {
            steps {
                sh 'echo "This is production branch"'
            }
        }

        stage('sprint1') {
            steps {
                sh 'echo "sprint1 application..."'
            }
        }

        stage('Deploy application') {
            steps {
                sh 'echo "Deploying application..."'
            }
        }
    }
}
