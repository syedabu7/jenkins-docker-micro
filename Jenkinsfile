// pipeline {

//     // agent any

//     agent any

//     stages {

//         stage('Build') {

//             steps {


//                 echo "Build"
// 				echo "building in process"
// 				script { 
// 					docker image : docker push xxxxxxx
// 				}

//             }

//         }

//         stage('Test') {

//             steps {

//                 echo "Test"

//             }

//         }

//         stage('Integration Test') {

//             steps {

//                 echo "Integration Test"

//             }

//         }

//     }

   

//     post {

//         always {

//             echo "I'm awesome, I always run!"

//         }

//         success {

//             echo "I run when when you successful"

//         }

//         failure {

//             echo "I run when when   you fail"

//         }

//     }




// }

pipeline {

    // agent any

    agent { docker { image 'maven:3.6.3' } }

    stages {

        stage('Build') {

            steps {

                sh 'mvn --version'

                echo "Build"

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
