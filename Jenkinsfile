pipeline {
    agent any

    stages {
        stage('Test Docker') {
            steps {
                sh 'docker version'
                sh 'docker container run -dt --name hp-app redis'
            }
        }
    }
}
