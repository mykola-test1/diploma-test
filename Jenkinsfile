pipeline {
    agent any

    stages {
        stage('Run Script') {
            steps {
                sh 'python main.py'
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
