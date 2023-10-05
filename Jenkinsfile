pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                echo "this is the building stage"
            }
        }
        stage('test'){
            steps{
                echo 'thsi is the testing stage'
            }

        }
        parallel{
            stage('para'){
                steps{
                    echo "this is the parallel stage 1"
                }
            }
            stage('para2'){
                steps{
                    echo "thsi is the parallelstage 2"
                }
            }
        }
    }

}

 