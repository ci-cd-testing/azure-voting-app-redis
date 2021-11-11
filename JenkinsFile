pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('GoodBye') {
            steps {
                echo 'Goodbye cruel World'
            }
        }
        stage('Variables') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
    }
}
