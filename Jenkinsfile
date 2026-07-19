pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'code laqu'
            }
        }
        stage('Build') {
            steps {
                echo 'start build'
            }
        }
        stage('test') {
            steps {
                echo 'start test'
            }
        }
    post {
         success {
             echo 'Pipeline success'
              }
          }
        }



