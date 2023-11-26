pipeline {
    agent any

    stages {
        stage ('SCM') {
            steps {
                git branch: 'main', url: 'https://github.com/pythoncpp/jenkins-html-demo.git'
            }
        }
        stage ('python file') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}
