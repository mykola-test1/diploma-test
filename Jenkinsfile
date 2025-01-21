pipeline {
    agent any

    stages {
        stage('Run Script') {
            steps {
                sh 'python3 main.py'
            }
        }
    }

    post {
        success {
            echo 'Build succeeded!'
        }
        failure {
            echo 'Build failed!'
        }
    }
}
