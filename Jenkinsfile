pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Eric!"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
