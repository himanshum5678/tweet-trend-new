pipeline {
    agent {
        node {
            label 'slave1'
        }
    }

    stages {
        stage("Build"){
            steps {
                sh "/usr/bin/mvn clean deploy"
            }
        }
    }
}
