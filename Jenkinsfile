pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                echo 'Running build automation update'
                mvn clean install
            }
        }
    }
}
