pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], userRemoteConfigs: [[url: 'https://github.com/your-username/your-repo.git']]])
            }
        }

        // Add more stages as needed
    }
}
