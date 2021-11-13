pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo "Hello World"'
                bat '''
                    echo "Multiline shell steps works too"
                    dir
                    echo "Checking polling"
                    echo "new branch created"
                    echo "Its working"
                '''
            }
        }
    }
}
