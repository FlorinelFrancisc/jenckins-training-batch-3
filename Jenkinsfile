pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo "Cloning the repository..."
                // Jenkins already checks out the code, so this is optional
                sh 'ls -la'
            }
        }

        stage('Print Hello & System Info') {
            steps {
                sh '''
                    echo "Hello from Jenkins Pipeline!"
                    date
                    pwd
                    whoami
                '''
            }
        }
    }
}
