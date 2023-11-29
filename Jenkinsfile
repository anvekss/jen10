pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
            steps {
                echo 'Hello World'
                sh 'python testpysa.py'
            }
        }
    }
}
