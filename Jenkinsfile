pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }

        stage('Test') {
            steps {
                sh 'pip install pytest'
                sh 'pytest'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment done!'
            }
        }
    }
}
