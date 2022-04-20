pipeline {

    agent any

    stages {

        stage('Build') {

            steps {

           echo "build"    

                sh "javac helloworld.java"

            }

        }

        stage('execute') {

            steps {

               echo "test"

                sh "java helloworld"

            }

        }

        stage('Deploy') {

            steps {

              echo "deploy"

            }

        }

    }

<<<<<<< HEAD
}

=======
>>>>>>> 7d84fb076e8da977a257fbe053eae0fd33f87700

