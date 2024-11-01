pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/Jagan0816/tweet-trend-new.git'
            }
        }
    }
}
