pipeline {
    agent any

    stages {
        stage ("install dependencies") {
            steps {
                scripts {
                    echo "Installing dependencies"
                }
            }
        }

        stage ("build app") {
            steps {
                script {
                    echo "Building app"
                }
            }
        }

        stage ("deploy app") {
            steps {
                script {
                    echo "Deploying app"
                }
            }
        }
    }
}