pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'docker run hello-world'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}