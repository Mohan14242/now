pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "This is the building stage"
            }
        }
        stage('test') {
            steps {
                echo 'This is the testing stage'
            }
        }
        parallel {
            stage('para') {
                steps {
                    echo "This is parallel stage 1"
                }
            }
            stage('para2') {
                steps {
                    echo "This is parallel stage 2"
                }
            }
        }
    }
}

