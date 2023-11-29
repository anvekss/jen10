pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo "python3 %WORKSPACE%\\testpysa.py"
            }
        }
    }
}
