pipeline {
    agent {
        node {
            label 'maven'
        }
    }
    stages {
        stage('Clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/minotaur423/tweet-trend-new.git'
            }
        }
    }
}