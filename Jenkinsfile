pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build Step 1'
            }
            steps {
                echo 'Build Step 2'
            }
            steps {
                echo 'Build Step 3'
            }
            steps {
                echo 'Build Step 4'
            }
        }

        stage('Test') {
            steps {
                echo 'Test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy'
            }
        }
    }

    post{
        always{
            echo "Always Running"
        }

        success{
            echo "Yay, success!"
        }

        failure{
            echo "Oh no, failure!"
        }

        cleanup {
            echo "Don't care success or error"
        }

    }
}

   
