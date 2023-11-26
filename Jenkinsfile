pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout([branches: [[name: '*/master']], userRemoteConfigs: [[url: 'https://github.com/your-username/your-repo.git']]])
            }
        }

    }
}
