pipeline {

    agent any

    stages {

        stage('Build') {

            steps {
 

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


