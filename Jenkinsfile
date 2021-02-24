
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh "git clone git@github.com:brave321/dev.git"
            }
        }
    }
}
