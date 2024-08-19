pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Lone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/Vardhan4devops/tweet-trend-new.git'
            }
        }
    }
}