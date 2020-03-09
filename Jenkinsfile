pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Running build automation update'
                sh 'mvn clean install'
            }
        }
    }
}
