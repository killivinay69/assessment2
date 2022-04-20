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


