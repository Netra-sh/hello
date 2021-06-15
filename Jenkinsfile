pipeline {
    agent any
    triggers {
        pollSCM '* * * * *'
      }

    stages {
        stage('Build') {
            steps {
                git "https://github.com/Netra-sh/hello.git"
         
            }
        }
    }
}
