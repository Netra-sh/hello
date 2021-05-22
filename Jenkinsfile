pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/Netra-sh/hello.git'
                sh './mvnw clean compile'
            }
        }
    }
}
