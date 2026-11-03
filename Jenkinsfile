pipeline {
    agent any // <-- This allocates the required node/workspace context
    
    stages {
        stage('Run Script') {
            steps {
                sh './say_hello.sh'
            }
        }
    }
}
