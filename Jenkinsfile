pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    echo "Multiline shell steps works too 2x"
                    ls -sh
                    ls -lah
                '''
            }
        }
    }
}
