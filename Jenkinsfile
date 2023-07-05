pipeline {

    // agent any

    agent any

    stages {

        stage('Build') {

            steps {


                echo "Build"
				echo "building in process"

            }

        }

        stage('Test') {

            steps {

                echo "Test"

            }

        }

        stage('Integration Test') {

            steps {

                echo "Integration Test"

            }

        }

    }

   

    post {

        always {

            echo "I'm awesome, I always run!"

        }

        success {

            echo "I run when when you successful"

        }

        failure {

            echo "I run when when   you fail"

        }

    }




}