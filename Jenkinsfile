pipeline {
    agent any
    stages {
         stage ('SCM-Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/rhodricgana/demo-demo.git'
            }

stage ('Unit testing') {
            steps {
                sh 'mvn test'
                }
            }
stage ('Intehgration testing') {
            steps {
                sh 'mvn test -Dtest=**/*Integration'
            }
           
        }
    }
}