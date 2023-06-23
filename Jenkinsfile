pipeline {
    agent any
    stages {
         stage ('SCM-Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/rhodricgana/demo-demo.git'
            }
        }
    }
}
