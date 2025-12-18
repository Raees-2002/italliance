pipeline {
    agent any

    stages {
        stage('test-002') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Raees-2002/italliance.git'
            }
        }

        stage('Build') {
            steps {
                sh '''
                echo "Build started"
                ls -la
                echo "Build completed"
                '''
            }
        }
    }
}
