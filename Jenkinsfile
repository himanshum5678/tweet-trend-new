pipeline {
    agent {
        node {
            label 'slave1'
        }
    }

    stages {
        stage('Git Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/himanshum5678/tweet-trend-new.git'
            }
        }
    }
}
