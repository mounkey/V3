pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git credentialsId: 'f55f1a42-548d-4ee4-8e86-d70559f01ad0', url: 'https://github.com/mounkey/V3.git'
            }
        }
    }
}